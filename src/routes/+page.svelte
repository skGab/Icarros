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
	import cta_logo from '$lib/images/cta-logo.webp';
	import cta_lupa from '$lib/icons/lupa-cta.svg';
	import cta_img from '$lib/images/cta-img.webp';
	import sell_icon from '$lib/icons/sell-icon.png';
	import service_icon from '$lib/icons/service-icon.png';
	import finance_icon from '$lib/icons/finance-icon.png';

	// SPLIDE SLIDE
	import { Splide, SplideSlide } from '@splidejs/svelte-splide';
</script>

<svelte:head>
	<title>manual icarros</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

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

			<!-- <div class="carousel-indicators progress">
                <div class="progress-bar w-25 text-secondary fw-bold" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">
                </div>
            </div> -->

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

				<Splide
					id="editorials_slide"
					options={{
						gap: '2rem',
						arrows: false,
						perPage: 3,
						breakpoints: {
							991: {
								perPage: 2
							},
							767: {
								perPage: 1
							}
						}
					}}
				>
					<SplideSlide>
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
					</SplideSlide>

					<SplideSlide>
						<div class="card w-100 h-100 p-2">
							<a href="/" class="card-body">
								<img
									loading="lazy"
									src={bussiness_icon}
									class="img-fluid mb-5"
									alt="Icone Negocios"
								/>
								<div class="d-flex align-items-center justify-content-between">
									<div class="info">
										<h3 class="card-title mb-1 h5 text-dark">negócios</h3>
										<h4 class="card-text text-secondary h6">ajuda para comprar e vender</h4>
									</div>
									<img src={arrow_right} class="img-fluid" alt="Seta para direita" />
								</div>
							</a>
						</div>
					</SplideSlide>

					<SplideSlide>
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
					</SplideSlide>

					<SplideSlide>
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
					</SplideSlide>

					<SplideSlide>
						<div class="card w-100 h-100 p-2">
							<a href="/" class="card-body">
								<img loading="lazy" src={web_icon} class="img-fluid mb-5" alt="Icone Globo" />
								<div class="d-flex align-items-center justify-content-between">
									<div class="info">
										<h3 class="card-title mb-1 h5 text-dark">na estrada</h3>
										<h4 class="card-text text-secondary h6">
											histórias e experiências sobre rodas
										</h4>
									</div>
									<img src={arrow_right} class="img-fluid" alt="Seta para direita" />
								</div>
							</a>
						</div>
					</SplideSlide>

					<SplideSlide>
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
					</SplideSlide>
				</Splide>
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

				<Splide
					id="content_slide"
					options={{
						arrows: false,
						gap: '1.5rem',
						perPage: 3,
						breakpoints: {
							991: {
								perPage: 2
							},
							767: {
								perPage: 1
							}
						}
					}}
				>
					<SplideSlide>
						<div class="card w-100 h-100 p-2">
							<div class="card-body text-white d-flex flex-column justify-content-between">
								<span class="border border-1 border-white rounded-3 px-2">lorem ipsum</span>
								<div>
									<h3 class="card-text h6 lh-base">
										icarros aponta aumento de 500% na busca por híbridos nos últimos meses
									</h3>
									<button class="btn p-0">
										<a href="/" class="h6"
											>ver matéria
											<img
												loading="lazy"
												src={arrow_right_white}
												class="img-fluid"
												alt="Icone seta direita"
											/>
										</a>
									</button>
								</div>
							</div>
						</div>
					</SplideSlide>

					<SplideSlide>
						<div class="card w-100 h-100 p-2">
							<div class="card-body text-white d-flex flex-column justify-content-between">
								<span class="border border-1 border-white rounded-3 px-2">lorem ipsum</span>
								<div>
									<h3 class="card-text h6 lh-base">
										icarros aponta aumento de 500% na busca por híbridos nos últimos meses
									</h3>
									<button class="btn p-0">
										<a href="/" class="h6"
											>ver matéria
											<img
												loading="lazy"
												src={arrow_right_white}
												class="img-fluid"
												alt="Icone seta direita"
											/>
										</a>
									</button>
								</div>
							</div>
						</div>
					</SplideSlide>

					<SplideSlide>
						<div class="card w-100 h-100 p-2">
							<div class="card-body text-white d-flex flex-column justify-content-between">
								<span class="border border-1 border-white rounded-3 px-2">lorem ipsum</span>
								<div>
									<h3 class="card-text h6 lh-base">
										icarros aponta aumento de 500% na busca por híbridos nos últimos meses
									</h3>
									<button class="btn p-0">
										<a href="/" class="h6"
											>ver matéria
											<img
												loading="lazy"
												src={arrow_right_white}
												class="img-fluid"
												alt="Icone seta direita"
											/>
										</a>
									</button>
								</div>
							</div>
						</div>
					</SplideSlide>

					<SplideSlide>
						<div class="card w-100 h-100 p-2">
							<div class="card-body text-white d-flex flex-column justify-content-between">
								<span class="border border-1 border-white rounded-3 px-2">lorem ipsum</span>
								<div>
									<h3 class="card-text h6 lh-base">
										icarros aponta aumento de 500% na busca por híbridos nos últimos meses
									</h3>
									<button class="btn p-0">
										<a href="/" class="h6"
											>ver matéria
											<img
												loading="lazy"
												src={arrow_right_white}
												class="img-fluid"
												alt="Icone seta direita"
											/>
										</a>
									</button>
								</div>
							</div>
						</div>
					</SplideSlide>

					<SplideSlide>
						<div class="card w-100 h-100 p-2">
							<div class="card-body text-white d-flex flex-column justify-content-between">
								<span class="border border-1 border-white rounded-3 px-2">lorem ipsum</span>
								<div>
									<h3 class="card-text h6 lh-base">
										icarros aponta aumento de 500% na busca por híbridos nos últimos meses
									</h3>
									<button class="btn p-0">
										<a href="/" class="h6"
											>ver matéria
											<img
												loading="lazy"
												src={arrow_right_white}
												class="img-fluid"
												alt="Icone seta direita"
											/>
										</a>
									</button>
								</div>
							</div>
						</div>
					</SplideSlide>

					<SplideSlide>
						<div class="card w-100 h-100 p-2">
							<div class="card-body text-white d-flex flex-column justify-content-between">
								<span class="border border-1 border-white rounded-3 px-2">lorem ipsum</span>
								<div>
									<h3 class="card-text h6 lh-base">
										icarros aponta aumento de 500% na busca por híbridos nos últimos meses
									</h3>
									<button class="btn p-0">
										<a href="/" class="h6"
											>ver matéria
											<img
												loading="lazy"
												src={arrow_right_white}
												class="img-fluid"
												alt="Icone seta direita"
											/>
										</a>
									</button>
								</div>
							</div>
						</div>
					</SplideSlide>

					<SplideSlide>
						<div class="card w-100 h-100 p-2">
							<div class="card-body text-white d-flex flex-column justify-content-between">
								<span class="border border-1 border-white rounded-3 px-2">lorem ipsum</span>
								<div>
									<h3 class="card-text h6 lh-base">
										icarros aponta aumento de 500% na busca por híbridos nos últimos meses
									</h3>
									<button class="btn p-0">
										<a href="/" class="h6"
											>ver matéria
											<img
												loading="lazy"
												src={arrow_right_white}
												class="img-fluid"
												alt="Icone seta direita"
											/>
										</a>
									</button>
								</div>
							</div>
						</div>
					</SplideSlide>

					<SplideSlide>
						<div class="card w-100 h-100 p-2">
							<div class="card-body text-white d-flex flex-column justify-content-between">
								<span class="border border-1 border-white rounded-3 px-2">lorem ipsum</span>
								<div>
									<h3 class="card-text h6 lh-base">
										icarros aponta aumento de 500% na busca por híbridos nos últimos meses
									</h3>
									<button class="btn p-0">
										<a href="/" class="h6"
											>ver matéria
											<img
												loading="lazy"
												src={arrow_right_white}
												class="img-fluid"
												alt="Icone seta direita"
											/>
										</a>
									</button>
								</div>
							</div>
						</div>
					</SplideSlide>
				</Splide>
			</div>
		</div>
	</div>
</section>

<!-- CTA -->
<section id="cta">
	<div class="container px-4">
		<div class="row">
			<div class="col mx-auto">
				<div class="card w-100 py-3 py-lg-0">
					<div
						class="card-body text-center d-lg-flex align-items-center justify-content-around py-lg-0 px-xl-5 gap-3"
					>
						<figure class="logo mb-lg-0">
							<img loading="lazy" src={cta_logo} class="img-fluid" alt="Icarros Logo" />
						</figure>

						<p
							class="card-text fw-bold text-white border border-2 rounded-top  mx-auto p-3 d-lg-none"
						>
							Por aqui você faz tudo: <br />
							compra, vende e financia
						</p>

						<div class="d-none d-lg-flex flex-column py-3">
							<span
								class="text-white fw-bold mb-2"
								data-aos="fade-right"
								data-aos-anchor-placement="bottom-bottom"
								data-aos-duration="1000"
							>
								<img loading="lazy" src={cta_lupa} class="img-fluid" alt="Icone Lupa" />
								carro econômico para
							</span>
							<strong
								class="h2 bg-white py-3 px-3 px-xxl-4 fw-bold mb-1"
								data-aos="fade-left"
								data-aos-anchor-placement="bottom-bottom"
								data-aos-duration="1000">VIAJAR COM OS AMIGOS</strong
							>
						</div>

						<figure class="car mb-lg-0 align-self-end">
							<img loading="lazy" src={cta_img} class="img-fluid" alt="Imagem CTA" />
						</figure>

						<a
							href="/"
							class="btn fw-bold px-4 px-lg-3 py-2"
							style="min-width: 189px;"
							data-aos="fade-left"
							data-aos-anchor-placement="bottom-bottom"
							data-aos-duration="1800"
							>acesse o site
							<img
								loading="lazy"
								src={arrow_right}
								width="25px"
								class="img-fluid"
								alt="Seta para direita"
							/>
						</a>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<!-- GALLERY -->
<section id="gallery">
	<div class="container px-4">
		<div class="row">
			<div class="col">
				<Splide
					id="gallery_slide"
					options={{
						arrows: false,
						gap: '1.5rem',
						perPage: 3,
						breakpoints: {
							991: {
								perPage: 2
							},
							767: {
								perPage: 1
							}
						}
					}}
				>
					<SplideSlide>
						<div class="card w-100 h-100 p-2" />
					</SplideSlide>

					<SplideSlide>
						<div class="card w-100 h-100 p-2" />
					</SplideSlide>

					<SplideSlide>
						<div class="card w-100 h-100 p-2" />
					</SplideSlide>
				</Splide>
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

				<Splide
					id="services_slide"
					options={{
						arrows: false,
						gap: '2rem',
						perPage: 3,
						breakpoints: {
							991: {
								perPage: 2
							},
							576: {
								perPage: 1
							}
						}
					}}
				>
					<SplideSlide>
						<div class="card w-100 h-100 p-2 justify-content-center">
							<a href="/">
								<div class="card-body d-flex flex-column justify-content-between align-items-start">
									<img
										loading="lazy"
										src={service_icon}
										class="img-fluid mb-4"
										alt="Icone Serviço"
									/>
									<div class="d-flex align-items-center justify-content-between w-100">
										<div class="info">
											<h3 class="card-title mb-1 h6 text-dark">comprar</h3>
											<h4 class="card-tex text-secondary small">acesse e confira</h4>
										</div>
										<img src={arrow_right} class="img-fluid" alt="Seta para direita" />
									</div>
								</div>
							</a>
						</div>
					</SplideSlide>

					<SplideSlide>
						<div class="card w-100 h-100 p-2 justify-content-center">
							<a href="/">
								<div class="card-body d-flex flex-column justify-content-between align-items-start">
									<img
										loading="lazy"
										src={finance_icon}
										class="img-fluid mb-4"
										alt="Icone Finanças"
									/>
									<div class="d-flex align-items-center justify-content-between w-100">
										<div class="info">
											<h3 class="card-title mb-1 h6 text-dark">vender</h3>
											<h4 class="card-tex text-secondary small">acesse e confira</h4>
										</div>
										<img src={arrow_right} class="img-fluid" alt="Seta para direita" />
									</div>
								</div>
							</a>
						</div>
					</SplideSlide>

					<SplideSlide>
						<div class="card w-100 h-100 p-2 justify-content-center">
							<a href="/">
								<div class="card-body d-flex flex-column justify-content-between align-items-start">
									<img loading="lazy" src={sell_icon} class="img-fluid mb-4" alt="Icone Venda" />
									<div class="d-flex align-items-center justify-content-between w-100">
										<div class="info">
											<h3 class="card-title mb-1 h6 text-dark">
												conheça os tipos de financiamento com o icarros
											</h3>
											<h4 class="card-tex text-secondary small">
												opções de financiamento e simulações
											</h4>
										</div>
										<img src={arrow_right} class="img-fluid" alt="Seta para direita" />
									</div>
								</div>
							</a>
						</div>
					</SplideSlide>
				</Splide>
			</div>
		</div>
	</div>
</section>

<style>
</style>
