<script lang="ts">
	import logo_mobile from '$lib/images/logo_mobile.webp';
	import logo_manual_icarros from '$lib/images/logo_manual_icarros.webp';
	import menu_hamburguer from '$lib/icons/menu-hamburguer.png';
</script>

<header
	class="border-bottom mb-lg-5"
	data-aos="fade-down"
	data-aos-anchor-placement="top-bottom"
	data-aos-duration="950"
>
	<nav id="yellow_nav" class="navbar navbar-expand-lg navbar-light d-none d-lg-block">
		<div class="container justify-content-end px-4">
			<ul class="m-0 p-0 d-flex gap-3 text-white text-decoration-underline small">
				<li><a href="/">quem somos</a></li>
				<li><a href="/">ajuda</a></li>
				<li><a href="/">fale conosco</a></li>
			</ul>
		</div>
	</nav>

	<nav class="navbar navbar-expand-lg navbar-light">
		<div class="container px-4">
			<figure class="mb-0 navbar-brand">
				<a href="/index.php">
					<img src={logo_mobile} class="img-fluid d-lg-none" alt="Logo Icarros" />
					<img src={logo_manual_icarros} class="img-fluid d-none d-lg-block" alt="Logo Icarros" />
				</a>
			</figure>

			<button
				class="navbar-toggler p-0 border-0"
				type="button"
				data-bs-toggle="collapse"
				data-bs-target="#navbarSupportedContent"
				aria-controls="navbarSupportedContent"
				aria-expanded="false"
				aria-label="Toggle navigation"
			>
				<img src={menu_hamburguer} class="img-fluid" alt="Menu Hamburguer" />
			</button>

			<div class="collapse navbar-collapse flex-grow-0" id="navbarSupportedContent">
				<ul class="navbar-nav mx-auto mb-2 mb-lg-0 align-items-end">
					<li class="nav-item">
						<a class="nav-link active" href="/">mobilidade</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="/">negócios</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="/">você e seu carro</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="/">na garagem</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="/">na estrada</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="/">institucional</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="/">icarros</a>
					</li>
				</ul>
			</div>
		</div>
	</nav>
</header>

<style lang="scss">
	

	header {
		// HEADER
		.navbar-toggler:focus {
			box-shadow: none;
		}

		// nav:first-child {
		//   background-color: var(--roxo);
		// }

		a:hover {
			color: var(--laranja-claro) !important;
		}
	}
</style>
