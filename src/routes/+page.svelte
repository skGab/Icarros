<!-- SCRIPTS -->
<script lang="ts">
	// ICONS AND IMAGES
	import banner_hero from '$lib/images/banner_hero.webp';
	import lupa from '$lib/icons/lupa.png';
	import circulo from '$lib/icons/circulo.png';
	import arrow_right_white from '$lib/icons/arrow-right-white.png';
	import arrow_right from '$lib/icons/arrow-right.png';
	import place from '$lib/icons/place.png';
	import bussiness_icon from '$lib/icons/bussiness-icon.png';
	import manuntance_icon from '$lib/icons/manuntance-icon.png';
	import insuranceAuto from '$lib/icons/insuranceAuto.png';
	import web_icon from '$lib/icons/web-icon.png';
	import person_icon from '$lib/icons/person-icon.png';

	// SPLIDE SLIDE
	import ContentSlide from '$lib/components/slides/ContentSlide.svelte';
	import EditorialsSlide from '$lib/components/slides/EditorialsSlide.svelte';
	import GallerySlide from '$lib/components/slides/GallerySlide.svelte';
	import ServicesSlide from '$lib/components/slides/ServicesSlide.svelte';
	import Cta from '$lib/components/Cta.svelte';
</script>

<!-- HEAD -->
<svelte:head>
	<title>manual icarros</title>
	<meta name="description" content="O manual da Icarros" />
</svelte:head>

<!-- HERO -->
<section id="hero">
	<div class="container-lg px-0 px-lg-4">
		<div id="carouselHero" class="carousel slide" data-bs-ride="carousel" data-bs-interval="4500">
			<div class="carousel-indicators">
				<button
					type="button"
					data-bs-target="#carouselHero"
					data-bs-slide-to="0"
					class="active"
					aria-current="true"
					aria-label="Slide 1"
				/>
				<button
					type="button"
					data-bs-target="#carouselHero"
					data-bs-slide-to="1"
					class="active"
					aria-current="true"
					aria-label="Slide 2"
				/>
				<button
					type="button"
					data-bs-target="#carouselHero"
					data-bs-slide-to="2"
					class="active"
					aria-current="true"
					aria-label="Slide 3"
				/>
			</div>

			<div class="carousel-inner">
				<div class="carousel-item active">
					<img loading="lazy" src={banner_hero} class="d-block w-100 img-fluid" alt="Banner" />
					<div class="carousel-caption container d-flex flex-column justify-content-center">
						<h1
							class="h3 m-0 fw-bold d-block mb-4 lh-base"
							data-aos="fade-right"
							data-aos-duration="1500"
						>
							icarros aponta aumento de <br class="d-none d-lg-block" /> 500% na busca por híbridos
							<br class="d-none d-lg-block" /> nos últimos meses
						</h1>
						<button
							class="btn-content btn px-4 py-2"
							style="width: fit-content;"
							data-aos="fade-right"
							data-aos-duration="1500"
						>
							<a href="/" class="h5">ver conteúdo</a>
						</button>
					</div>
				</div>
				<div class="carousel-item">
					<img loading="lazy" src={banner_hero} class="d-block w-100 img-fluid" alt="Banner" />
					<div class="carousel-caption container d-flex flex-column justify-content-center">
						<h1 class="h3 m-0 fw-bold d-block mb-4 lh-base">
							icarros aponta aumento de <br class="d-none d-lg-block" /> 500% na busca por híbridos
							<br class="d-none d-lg-block" /> nos últimos meses
						</h1>
						<button class="btn-content btn px-4 py-2" style="width: fit-content;">
							<a href="/" class="h5">ver conteúdo</a>
						</button>
					</div>
				</div>
				<div class="carousel-item">
					<img loading="lazy" src={banner_hero} class="d-block w-100 img-fluid" alt="Banner" />
					<div class="carousel-caption container d-flex flex-column justify-content-center ">
						<h1 class="h3 m-0 fw-bold d-block mb-4 lh-base">
							icarros aponta aumento de <br class="d-none d-lg-block" /> 500% na busca por híbridos
							<br class="d-none d-lg-block" /> nos últimos meses
						</h1>
						<button class="btn-content btn px-4 py-2" style="width: fit-content;">
							<a href="/" class="h5">ver conteúdo</a>
						</button>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<!-- SEARCH CONTENT -->
<section id="search_content">
	<div class="container px-4">
		<div class="row">
			<div class="col-12 col-lg-8 mb-3">
				<form action="#">
					<div class="input-group p-3 align-items-center justify-content-between gap-sm-3">
						<img loading="lazy" src={lupa} class="img-fluid" alt="Icone Lupa" />
						<input
							class="border-0 w-75 p-0 m-0 flex-sm-grow-1"
							type="search"
							placeholder="digite o conteúdo que você procura"
							aria-label="Search"
						/>
						<img
							loading="lazy"
							src={circulo}
							class="img-fluid align-self-end"
							alt="Icone Circulo"
						/>
					</div>
				</form>
			</div>
			<div class="col-12 col-lg-4">
				<button class="btn w-100 p-3 d-flex align-items-center justify-content-between">
					<a href="/" class="fw-bold h6 m-0">ver notícias</a>
					<img loading="lazy" src={arrow_right_white} class="img-fluid" alt="Icone seta direita" />
				</button>
			</div>
		</div>
	</div>
</section>

<!-- EDITORIALS -->
<section id="editorials">
	<div class="container px-4">
		<div class="row d-lg-none">
			<div class="col">
				<h2
					class="fw-bold mb-3 mb-lg-4"
					data-aos="fade-right"
					data-aos-anchor-placement="bottom-bottom"
					data-aos-duration="950"
				>
					busque por assuntos no manual icarros
				</h2>

				<EditorialsSlide />
			</div>
		</div>

		<div class="row d-none d-lg-flex">
			<h2
				class="fw-bold mb-3 mb-lg-4"
				data-aos="fade-right"
				data-aos-anchor-placement="bottom-bottom"
				data-aos-duration="950"
			>
				busque por assuntos no manual icarros
			</h2>

			<div class="col-4 mb-4">
				<div class="card w-100 h-100 p-2">
					<a href="/" class="card-body">
						<img loading="lazy" src={place} class="img-fluid mb-5" alt="Icone Localização" />
						<div class="d-flex align-items-center justify-content-between">
							<div class="info">
								<h3 class="card-title mb-1 h5 text-dark">mobilidade</h3>
								<h4 class="card-text text-secondary h6">para todos que se movem</h4>
							</div>
							<img src={arrow_right} class="img-fluid" alt="Seta para direita" />
						</div>
					</a>
				</div>
			</div>
			<div class="col-4 mb-4">
				<div class="card w-100 h-100 p-2">
					<a href="/" class="card-body">
						<img loading="lazy" src={bussiness_icon} class="img-fluid mb-5" alt="Icone Negocios" />
						<div class="d-flex align-items-center justify-content-between">
							<div class="info">
								<h3 class="card-title mb-1 h5 text-dark">negócios</h3>
								<h4 class="card-text text-secondary h6">ajuda para comprar e vender</h4>
							</div>
							<img src={arrow_right} class="img-fluid" alt="Seta para direita" />
						</div>
					</a>
				</div>
			</div>
			<div class="col-4 mb-4">
				<div class="card w-100 h-100 p-2">
					<a href="/" class="card-body">
						<img
							loading="lazy"
							src={manuntance_icon}
							class="img-fluid mb-5"
							alt="Icone Manutenção"
						/>
						<div class="d-flex align-items-center justify-content-between">
							<div class="info">
								<h3 class="card-title mb-1 h5 text-dark">vc e seu carro</h3>
								<h4 class="card-text text-secondary h6">manutenção e dicas de cuidado</h4>
							</div>
							<img src={arrow_right} class="img-fluid" alt="Seta para direita" />
						</div>
					</a>
				</div>
			</div>
			<div class="col-4 mb-4">
				<div class="card w-100 h-100 p-2">
					<a href="/" class="card-body">
						<img loading="lazy" src={insuranceAuto} class="img-fluid mb-5" alt="Icone Carro" />
						<div class="d-flex align-items-center justify-content-between">
							<div class="info">
								<h3 class="card-title mb-1 h5 text-dark">na garagem</h3>
								<h4 class="card-text text-secondary h6">novidades do setor e avaliações</h4>
							</div>
							<img src={arrow_right} class="img-fluid" alt="Seta para direita" />
						</div>
					</a>
				</div>
			</div>
			<div class="col-4 mb-4">
				<div class="card w-100 h-100 p-2">
					<a href="/" class="card-body">
						<img loading="lazy" src={web_icon} class="img-fluid mb-5" alt="Icone Globo" />
						<div class="d-flex align-items-center justify-content-between">
							<div class="info">
								<h3 class="card-title mb-1 h5 text-dark">na estrada</h3>
								<h4 class="card-text text-secondary h6">histórias e experiências sobre rodas</h4>
							</div>
							<img src={arrow_right} class="img-fluid" alt="Seta para direita" />
						</div>
					</a>
				</div>
			</div>
			<div class="col-4 mb-4">
				<div class="card w-100 h-100 p-2">
					<a href="/" class="card-body">
						<img loading="lazy" src={person_icon} class="img-fluid mb-5" alt="Icone Pessoa" />
						<div class="d-flex align-items-center justify-content-between">
							<div class="info">
								<h3 class="card-title mb-1 h5 text-dark">institucional</h3>
								<h4 class="card-text text-secondary h6">estudos de mercado, dados e releses</h4>
							</div>
							<img src={arrow_right} class="img-fluid" alt="Seta para direita" />
						</div>
					</a>
				</div>
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
					class="fw-bold mb-3  mb-lg-4"
					data-aos="fade-left"
					data-aos-anchor-placement="bottom-bottom"
					data-aos-duration="950"
				>
					conteúdos recentes
				</h2>

				<ContentSlide />
			</div>
		</div>
	</div>
</section>

<!-- CTA -->
<section id="cta">
	<div class="container px-4">
		<div class="row">
			<div class="col mx-auto">
				<Cta />
			</div>
		</div>
	</div>
</section>

<!-- GALLERY -->
<section id="gallery">
	<div class="container px-4">
		<div class="row">
			<div class="col">
				<GallerySlide />
			</div>
		</div>
	</div>
</section>

<!-- SERVICES -->
<section id="services">
	<div class="container px-4">
		<div class="row">
			<div class="col">
				<h2
					class="fw-bold mb-3 mb-lg-4"
					data-aos="fade-right"
					data-aos-anchor-placement="bottom-bottom"
					data-aos-duration="950"
				>
					produtos e serviços do icarros
				</h2>

				<ServicesSlide />
			</div>
		</div>
	</div>
</section>

<!-- STYLE -->
<style lang="scss">
	@mixin animation($bg-color) {
		background-color: $bg-color;
		transition: all 0.5s ease;
	}
	@mixin brightnessEffect() {
		transition: all 0.2s ease-in;
		filter: brightness(150%);
	}
	@mixin shadowEffect() {
		transition: all 0.2s ease-in;
		filter: drop-shadow(1px 2px 4px rgba(0, 0, 0, 0.541));
	}

	// HOME PAGE
	#hero {
		.carousel-inner {
			.carousel-item {
				img {
					min-height: 498px;
					object-fit: cover;
					object-position: 50%;

					@media only screen and (min-width: 992px) {
						border-radius: 12px;
					}
				}

				.carousel-caption {
					top: 5%;
					bottom: 0;
					left: 0;
					right: 0;
					text-align: left;
					padding: 0 1.5rem;

					.btn-content {
						border: #ffffffe8 1px solid !important;
						border-radius: 0.5rem;
					}

					.btn-content:hover {
						border: var(--laranja-claro) 1px solid !important;
					}

					.btn-content:hover > a {
						color: var(--laranja-claro);
					}

					@media only screen and (min-width: 992px) {
						top: 0%;
						padding: 5rem;
					}
				}
			}

			@media only screen and (min-width: 992px) {
				border-radius: 12px;
			}
		}
	}

	#search_content {
		form {
			.input-group {
				border: 1px solid var(--cinza-escuro-borda);
				border-radius: 8px;
				background-color: #f2f2f2;
			}

			input {
				color: var(--preto);
				background: none;
			}

			input:focus {
				box-shadow: none;
				outline: none;
			}
		}

		button {
			background-color: var(--laranja-claro);
			border-radius: 8px;
			transition: all 0.2s ease-in;

			a:hover {
				color: var(--branco) !important;
			}

			a:focus {
				color: var(--branco);
			}
		}

		button:focus,
		button:hover {
			box-shadow: none;
			@include animation(rgb(26, 26, 26));
		}
	}

	#editorials,
	#recent_content,
	#gallery,
	#services {
		.card {
			border: #00000025 solid 1px;
			border-radius: 12px;

			letter-spacing: 0.1px;
		}

		.splide {
			.splide__pagination {
				position: unset;
				margin-top: 1.5rem;
			}
			.splide__pagination__page {
				border: var(--cinza-escuro-borda) solid 1px;
				background: none;
			}
			.splide__pagination__page.is-active {
				background-color: rgb(0, 0, 0);
			}

			.splide__arrow {
				background: none;
				top: 97%;
			}
			.splide__arrow--next {
				right: 25%;
				max-width: 1rem;
			}
			.splide__arrow--prev {
				left: 25%;
				max-width: 1rem;
			}

			@media screen and (min-width: 992px) {
				.splide__arrow--next {
					right: 45%;
					max-width: 1rem;
				}
				.splide__arrow--prev {
					left: 45%;
					max-width: 1rem;
				}
			}
		}
	}

	#editorials {
		.splide {
			.splide__slide {
				max-width: 368px;
			}
		}
	}

	#recent_content {
		.splide {
			.splide__slide {
				max-width: 320px;
			}
			.splide__arrow {
				background: none;
				top: 98%;
			}
		}
	}

	#gallery {
		.splide {
			.splide__slide {
				max-width: 368px;
			}
			.splide__arrow {
				background: none;
				top: 98%;
			}
		}
	}

	#services {
		.splide {
			.splide__slide {
				max-width: 368px;
			}

			@media screen and (min-width: 992px) {
				.splide__arrow {
					display: none;
				}
			}
		}
	}
</style>
