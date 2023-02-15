<!-- SCRIPTS -->
<script lang="ts">
	import Post from '$lib/components/Post.svelte';
	import ContentSlide from '$lib/components/slides/ContentSlide.svelte';
	import ServicesSlide from '$lib/components/slides/ServicesSlide.svelte';
</script>

<!-- HEAD -->
<svelte:head>
	<title>manual icarros - editorias</title>
	<meta name="description" content="O manual da Icarros" />
</svelte:head>

<!-- EDITORIA -->
<section id="editoria" class="mt-5">
	<div class="container px-4 px-lg-0">
		<div class="row">
			<div class="col">
				<div class="bg py-4 px-4 text-white">
					<h1 class="m-0 fw-bold" data-aos="fade-right" data-aos-duration="1800">mobilidade</h1>
					<p class="m-0" data-aos="fade-left" data-aos-duration="1800">para todos que se movem</p>
				</div>
			</div>
		</div>
	</div>
</section>

<!-- RECENT CONTENT -->
<section id="recent_content">
	<div class="container px-4">
		<div class="row d-lg-none">
			<div class="col">
				<h2
					class="fw-bold mb-4"
					data-aos="fade-right"
					data-aos-anchor-placement="bottom-bottom"
					data-aos-duration="950"
				>
					Últimos conteúdos do manual icarros
				</h2>

				<ContentSlide/>
			</div>
		</div>
		
		<div class="row d-none d-lg-flex">
			<h2
				class="fw-bold mb-4"
				data-aos="fade-right"
				data-aos-anchor-placement="bottom-bottom"
				data-aos-duration="950"
			>
				últimos conteúdos do manual icarros
			</h2>

			<Post />
			<Post />
			<Post />
			<Post />
			<Post />
			<Post />
			<Post />
			<Post />
			<Post />
			<Post />
			<Post />
			<Post />
			<Post />
		</div>
	</div>
</section>

<!-- STYLE -->
<style lang="scss">
	#editoria {
		.bg {
			border-radius: 20px;
			background-color: var(--roxo) !important;
		}
	}
</style>
