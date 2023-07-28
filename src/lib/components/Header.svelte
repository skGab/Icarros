<script lang="ts">
	import logo_icarros from '$lib/images/logo_manual.svg';
	import menu_hamburguer from '$lib/icons/menu-hamburguer.png';
</script>

<header class="border-bottom mb-lg-5">
	<nav id="yellow_nav" class="navbar navbar-expand-lg navbar-light d-none d-lg-block">
		<div class="container justify-content-end px-4">
			<ul class="m-0 p-0 d-flex gap-3 text-white text-decoration-underline small">
				<li><a href="/">quem somos</a></li>
				<li><a href="/">ajuda</a> </li>
				<li><a href="/">fale conosco</a> </li>
			</ul>
		</div>
	</nav>

	<nav class="navbar navbar-expand-lg navbar-light p-lg-0">
		<div class="container px-4">
			<figure class="mb-0 navbar-brand p-lg-0">
				<a href="/">
					<img
						src={logo_icarros}
						width="115px"
						class="img-fluid d-none d-lg-block"
						alt="Logo Icarros"
					/>
					<img src={logo_icarros} width="90px" class="img-fluid d-lg-none" alt="Logo Icarros" />
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
					<li class="nav-item px-2 px-lg-0 py-lg-3">
						<a class="nav-link" href="/">home</a>
					</li>
					<li class="nav-item px-2 px-lg-0 py-lg-3">
						<a class="nav-link" href="/editoria">editorias</a>
					</li>
					<li class="nav-item px-2 px-lg-0 py-lg-3">
						<a class="nav-link" href="/post">post</a>
					</li>
					<li class="nav-item px-2 px-lg-0 py-lg-3">
						<a class="nav-link" href="/">na garagem</a>
					</li>
					<li class="nav-item px-2 px-lg-0 py-lg-3">
						<a class="nav-link" href="/">na estrada</a>
					</li>
					<li class="nav-item px-2 px-lg-0 py-lg-3">
						<a class="nav-link" href="/">institucional</a>
					</li>
					<li class="nav-item px-2 px-lg-0 py-lg-3">
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
		.nav-item:hover {
			background-color: #d6d0cc;
			transition: all 0.5s ease;
			border-bottom: 1px solid var(--laranja-escuro);

			@media screen and (min-width: 992px) {
				height: 71px;
			}

			.nav-link {
				color: var(--preto) !important;
			}
		}

		.nav-link {
			color: var(--cinza-escuro-borda) !important;
			transition: all 0.5s ease;
		}

		#yellow_nav {
			background-color: var(--roxo);
		}
	}
</style>
