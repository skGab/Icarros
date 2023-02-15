<!-- SCRIPT -->
<script lang="ts">
	import arrow_right_white from '$lib/icons/arrow-right-white.png';
	import facebook from '$lib/icons/facebook.png';
	import instagram from '$lib/icons/instagram.png';
	import whatsapp from '$lib/icons/whatsapp.png';
	import share from '$lib/icons/share.png';
	import twitter from '$lib/icons/twitter.png';
	import Cta from '$lib/components/Cta.svelte';
	import CtaSingle from '$lib/components/CtaSingle.svelte';
	import ContentSlide from '$lib/components/slides/ContentSlide.svelte';
</script>

<!-- HEAD -->
<svelte:head>
	<title>manual icarros - post</title>
	<meta name="description" content="O manual da Icarros" />
</svelte:head>

<!-- BANNER HERO -->
<section id="banner_hero">
	<div class="container px-4 py-5 d-flex">
		<div class="row p-lg-5 mt-5">
			<div class="col col-lg-7">
				<h1 class="fw-bold text-white lh-base" data-aos="fade-left" data-aos-duration="1500">
					icarros aponta aumento de 500% na busca por hibridos nos ultimos meses
				</h1>
			</div>
		</div>
	</div>
</section>

<!-- MAIN CONTENT -->
<section id="main_content">
	<div class="container px-4">
		<div class="row mb-5 justify-content-between">
			<!-- POST CONTENT -->
			<div id="post_content" class="col-12 col-lg-8 mb-5 mb-lg-0">
				<p>
					um levantamento feito pelo icarros, marketplace automotivo do Itaú Unibanco, mostrou que a
					busca por automóveis híbridos na plataforma cresceu 5.726% no 3º trimestre de 2022 -
					número 58 vezes superior ao registrado no mesmo período em 2021.
				</p>

				<p>
					os cinco modelos híbridos mais pesquisados no icarros representaram 66% das buscas por
					todos os modelos com esse tipo de motorização. O mais buscado foi o Toyota Corolla 1.8
					Altis Hybrid, ocupando as 4 primeiras posições no ano-modelo 2020, seguido pelo 2021,
					versão Premium e Premium CVT. Na quinta posição ficou o Ford Fusion 2.9 Hybrid Titanium.
				</p>

				<h2
					class="fw-bold my-4"
					data-aos="fade-right"
					data-aos-placement="top-bottom"
					data-aos-duration="950"
				>
					aumento na busca de híbridos e elétricos
				</h2>

				<p>
					além do número expressivo na procura por estes modelos específicos, os dados também
					identificaram aumento de 219% nas consultas pelo combustível Híbrido/Elétrico, superando
					em três vezes a marca de julho a setembro do ano passado.
				</p>

				<p>
					um levantamento feito pelo icarros, marketplace automotivo do Itaú Unibanco, mostrou que a
					busca por automóveis híbridos na plataforma cresceu 5.726% no 3º trimestre de 2022 -
					número 58 vezes superior ao registrado no mesmo período em 2021.
				</p>

				<p>
					os cinco modelos híbridos mais pesquisados no icarros representaram 66% das buscas por
					todos os modelos com esse tipo de motorização. O mais buscado foi o Toyota Corolla 1.8
					Altis Hybrid, ocupando as 4 primeiras posições no ano-modelo 2020, seguido pelo 2021,
					versão Premium e Premium CVT. Na quinta posição ficou o Ford Fusion 2.9 Hybrid Titanium.
				</p>

				<h2
					class="fw-bold my-4"
					data-aos="fade-right"
					data-aos-placement="top-bottom"
					data-aos-duration="950"
				>
					aumento na busca de híbridos e elétricos
				</h2>

				<p class="m-0">
					além do número expressivo na procura por estes modelos específicos, os dados também
					identificaram aumento de 219% nas consultas pelo combustível Híbrido/Elétrico, superando
					em três vezes a marca de julho a setembro do ano passado.
				</p>
			</div>

			<!-- SIDEBAR -->
			<aside id="sidebar" class="col-12 col-lg-3">
				<!-- SOCIAL -->
				<div id="social" class="row mb-5">
					<div class="col-12 col-lg-12">
						<h2
							class="fw-bold mb-4 d-lg-none"
							data-aos="zoom-out-left"
							data-aos-placement="bottom-bottom"
							data-aos-duration="1500"
						>
							compartilhar nas redes:
						</h2>
						<h2
							class="fw-bold mb-4 h3 d-none d-lg-block"
							data-aos="zoom-out-left"
							data-aos-placement="bottom-bottom"
							data-aos-duration="1500"
						>
							compartilhar nas redes:
						</h2>

						<figure
							class="d-flex justify-content-between align-items-center mb-0 border border-dark px-4 py-3"
							style="border-radius: 12px;"
						>
							<a href="/">
								<img loading="lazy" src={whatsapp} class="img-fluid" alt="Icone Whatsapp" />
							</a>
							<a href="/">
								<img loading="lazy" src={instagram} class="img-fluid" alt="Icone Instagram" />
							</a>
							<a href="/">
								<img loading="lazy" src={twitter} class="img-fluid" alt="Icone Twitter" />
							</a>
							<a href="/">
								<img loading="lazy" src={facebook} class="img-fluid" alt="Icone Facebook" />
							</a>
							<a href="/">
								<img loading="lazy" src={share} class="img-fluid" alt="Icone Compartilhar" />
							</a>
						</figure>
					</div>
				</div>

				<!-- CTA -->
				<div id="cta" class="row">
					<div class="col-12 col-lg-12 mx-auto">
						<CtaSingle />
					</div>
				</div>
			</aside>
		</div>

		<div class="line row d-none d-lg-block">
			<div class="container my-5">
				<div class="col border" />
			</div>
		</div>
	</div>
</section>

<!-- RECENT CONTENT -->
<section id="recent_content">
	<div class="container px-4">
		<div class="row">
			<div class="col">
				<h2
					class="fw-bold mb-3"
					data-aos="fade-right"
					data-aos-anchor-placement="bottom-bottom"
					data-aos-duration="950"
				>
					você tambem pode gostar:
				</h2>

				<ContentSlide />
			</div>
		</div>
	</div>
</section>

<!-- EDITORIALS -->
<section id="editorials_single">
	<div class="container px-4">
		<div class="row flex-wrap">
			<h2
				class="fw-bold mb-3"
				data-aos="fade-down"
				data-aos-anchor-placement="bottom-bottom"
				data-aos-duration="950"
			>
				conheça nossas editorias:
			</h2>

			<div class="col-6">
				<ul
					class="d-flex flex-column flex-md-row p-0 m-0 justify-content-xxl-between align-items-md-center flex-md-wrap gap-4"
				>
					<a href="/">
						<li class="px-4 py-3 text-white fw-bold">mobilidade</li>
					</a>
					<a href="/">
						<li class="px-4 py-3 text-white fw-bold">negócios</li>
					</a>
					<a href="/">
						<li class="px-4 py-3 text-white fw-bold">vc e seu carro</li>
					</a>
				</ul>
			</div>

			<div class="col-6">
				<ul
					class="d-flex flex-column flex-md-row p-0 m-0 justify-content-xxl-between align-items-md-center flex-md-wrap gap-4"
				>
					<a href="/">
						<li class="px-4 py-3 text-white fw-bold">na garagem</li>
					</a>
					<a href="/">
						<li class="px-4 py-3 text-white fw-bold">na estrada</li>
					</a>
					<a href="/">
						<li class="px-4 py-3 text-white fw-bold">institucional</li>
					</a>
				</ul>
			</div>
		</div>
	</div>
</section>

<!-- STYLE -->
<style lang="scss">
	@mixin shadowEffect() {
		transition: all 0.2s ease-in;
		filter: drop-shadow(1px 2px 4px rgba(0, 0, 0, 0.541));
	}

	@mixin animation($bg-color) {
		background-color: $bg-color;
		transition: all 0.5s ease;
	}
	#banner_hero {
		min-height: 498px;
		background: url('../../lib/images/banner_hero.webp') center no-repeat;
		background-size: cover;

		@media screen and (min-width: 992px) {
			width: fit-content;
			margin: 0 auto 5rem auto;
			border-radius: 15px;
		}
	}

	#social {
		figure img:hover {
			@include shadowEffect();
		}
	}

	#editorials_single {
		li {
			background-color: var(--laranja-claro);
			border-radius: 10px;

			@media screen and (min-width: 768px) {
				min-width: 164px;
			}
		}

		li:hover {
			@include animation(var(--preto));
		}
	}
</style>
