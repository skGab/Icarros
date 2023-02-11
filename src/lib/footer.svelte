<script>
	import icarros_master_brand from '$lib/images/icarros-Master-Brand.png';
	import app_store from '$lib/icons/app-store.png';
	import play_store from '$lib/icons/play-store.png';
	import facebook_icon from '$lib/icons/facebook-icon.png';
	import instagram_icon from '$lib/icons/instagram-icon.png';
	import youtube_icon from '$lib/icons/youtube-icon.png';
</script>

<footer class="pt-lg-5">
	<section
		id="store_social"
		class="mt-5 mb-5"
		data-aos="fade-up"
		data-aos-anchor-placement="center-bottom"
		data-aos-duration="950"
	>
		<div class="logo container px-4 mb-5">
			<figure class="row mb-0">
				<div class="col">
					<img
						loading="lazy"
						decoding="async"
						src={icarros_master_brand}
						class="img-fluid"
						alt="Logo Icarros"
					/>
				</div>
			</figure>
		</div>

		<div class="social container px-4 d-lg-flex flex-row gap-5 align-items-center">
			<div class="row mb-5 mb-lg-0">
				<figure class="d-flex align-items-center m-0 col-12 gap-3 flex-wrap">
					<a href="/" target="_blank">
						<img loading="lazy" decoding="async" src={app_store} class="img-fluid" alt="AppStore" />
					</a>
					<a href="/" target="_blank">
						<img
							loading="lazy"
							decoding="async"
							src={play_store}
							class="img-fluid"
							alt="PlayStore"
						/>
					</a>
				</figure>
			</div>
			<div class="row">
				<div class="col-12">
					<ul class="gap-4 d-flex p-0 pb-4 pb-lg-0 m-0">
						<a href="/" target="_blank"
							><img
								loading="lazy"
								decoding="async"
								src={facebook_icon}
								class="img-fluid"
								alt="Icone Facebook"
							/></a
						>
						<a href="/" target="_blank"
							><img
								loading="lazy"
								decoding="async"
								src={instagram_icon}
								class="img-fluid"
								alt="Icone Instagram"
							/></a
						>
						<a href="/" target="_blank"
							><img
								loading="lazy"
								decoding="async"
								src={youtube_icon}
								class="img-fluid"
								alt="Icone Youtube"
							/></a
						>
					</ul>
				</div>
			</div>
		</div>
	</section>

	<div class="line my-5 d-none d-lg-block">
		<div class="container px-4 ">
			<div class="row">
				<div class="col-12 border" />
			</div>
		</div>
	</div>

	<section
		id="items"
		class="mb-5"
		data-aos="fade-up"
		data-aos-anchor-placement="center-bottom"
		data-aos-duration="950"
	>
		<div class="container px-4">
			<div class="row d-lg-none">
				<div class="col">
					<ul class="accordion accordion-flush p-0 m-0" id="accordionFlushExample">
						<li class="accordion-item border-bottom">
							<h2 class="accordion-header border-bottom" id="flush-headingOne">
								<button
									class="accordion-button collapsed px-0"
									type="button"
									data-bs-toggle="collapse"
									data-bs-target="/flush-collapseOne"
									aria-expanded="false"
									aria-controls="flush-collapseOne"
								>
									Item 01
								</button>
							</h2>
							<div
								id="flush-collapseOne"
								class="accordion-collapse collapse"
								aria-labelledby="flush-headingOne"
								data-bs-parent="/accordionFlushExample"
							>
								<div class="accordion-body">
									Placeholder content for this accordion, which is intended to demonstrate the <code
										>.accordion-flush</code
									> class. This is the first item's accordion body.
								</div>
							</div>
						</li>

						<li class="accordion-item border-bottom">
							<h2 class="accordion-header border-bottom" id="flush-headingTwo">
								<button
									class="accordion-button collapsed px-0 "
									type="button"
									data-bs-toggle="collapse"
									data-bs-target="/flush-collapseTwo"
									aria-expanded="false"
									aria-controls="flush-collapseTwo"
								>
									Item 02
								</button>
							</h2>
							<div
								id="flush-collapseTwo"
								class="accordion-collapse collapse"
								aria-labelledby="flush-headingTwo"
								data-bs-parent="/accordionFlushExample"
							>
								<div class="accordion-body">
									Placeholder content for this accordion, which is intended to demonstrate the <code
										>.accordion-flush</code
									> class. This is the second item's accordion body. Let's imagine this being filled
									with some actual content.
								</div>
							</div>
						</li>

						<li class="accordion-item">
							<h2 class="accordion-header border-bottom" id="flush-headingThree">
								<button
									class="accordion-button collapsed px-0"
									type="button"
									data-bs-toggle="collapse"
									data-bs-target="/flush-collapseThree"
									aria-expanded="false"
									aria-controls="flush-collapseThree"
								>
									Item 03
								</button>
							</h2>
							<div
								id="flush-collapseThree"
								class="accordion-collapse collapse"
								aria-labelledby="flush-headingThree"
								data-bs-parent="/accordionFlushExample"
							>
								<div class="accordion-body">
									Placeholder content for this accordion, which is intended to demonstrate the <code
										>.accordion-flush</code
									> class. This is the third item's accordion body. Nothing more exciting happening here
									in terms of content, but just filling up the space to make it look, at least at first
									glance, a bit more representative of how this would look in a real-world application.
								</div>
							</div>
						</li>
					</ul>
				</div>
			</div>

			<div class="row d-none d-lg-flex">
				<div class="col">
					<h3 class="orange h6 fw-bold mb-4">item 01</h3>
					<ul class="p-0 m-0 small d-flex flex-column gap-4">
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
					</ul>
				</div>
				<div class="col">
					<h3 class="orange h6 fw-bold mb-4">item 02</h3>

					<ul class="p-0 m-0 small d-flex flex-column gap-4">
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
					</ul>
				</div>
				<div class="col">
					<h3 class="orange h6 fw-bold mb-4">item 03</h3>

					<ul class="p-0 m-0 small d-flex flex-column gap-4">
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
					</ul>
				</div>
				<div class="col">
					<h3 class="orange h6 fw-bold mb-4">item 04</h3>
					<ul class="p-0 m-0 small d-flex flex-column gap-4">
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
					</ul>
				</div>
				<div class="col">
					<h3 class="orange h6 fw-bold mb-4">item 05</h3>
					<ul class="p-0 m-0 small d-flex flex-column gap-4">
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
						<li class="fw-bold">
							<a href="/" class="text-dark">subitem 01.1</a>
						</li>
					</ul>
				</div>
			</div>
		</div>
	</section>

	<div class="line my-5 d-none d-lg-block">
		<div class="container px-4 ">
			<div class="row">
				<div class="col-12 border" />
			</div>
		</div>
	</div>

	<section
		id="adress"
		data-aos="fade-up"
		data-aos-anchor-placement="top-bottom"
		data-aos-duration="950"
	>
		<div class="container px-4">
			<div class="row">
				<div class="col-12">
					<p class="small mb-0">
						iCarros Ltda: Av. Presidente Juscelino Kubitschek, 180 2º Andar - Itaim Bibi - São Paulo
						SP CEP 04543-000 - CNPJ: 03.991.201/0001-96
					</p>
				</div>
			</div>
		</div>
	</section>
</footer>

<style>
</style>
