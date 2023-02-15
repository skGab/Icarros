<script lang="ts">
	import arrow_right from '$lib/icons/arrow-right.png';
	import cta_logo from '$lib/images/cta-logo.webp';
	import cta_lupa from '$lib/icons/lupa-cta.svg';
	import cta_img from '$lib/images/cta-img.webp';
</script>

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
								class="h2 bg-white py-3 px-3 px-xxl-4 fw-bold mb-1 d-none d-xxl-block"
								data-aos="fade-left"
								data-aos-anchor-placement="bottom-bottom"
								data-aos-duration="1000">VIAJAR COM OS AMIGOS</strong
							>
							<strong
								class="h5 bg-white py-3 px-3 px-xxl-4 fw-bold mb-1 d-xxl-none"
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
								width="20px"
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

<style lang="scss">
	@mixin animation($bg-color) {
		background-color: $bg-color;
		transition: all 0.5s ease;
	}

	#cta {
		.card {
			background-color: var(--laranja-claro);
			border-radius: 20px;

			p {
				width: fit-content;
				border-radius: 15px;
			}

			a {
				color: var(--branco);
				background-color: var(--cinza-escuro-borda);
				border-radius: 8px;
			}

			a:hover {
				@include animation(#ffffff);
				color: var(--cinza-escuro-borda);
			}

			strong {
				border-radius: 0 0 15px 15px;
				color: var(--laranja-claro);
			}

			.logo > img {
				@media only screen and (min-width: 992px) {
					max-width: 132px;
				}
			}

			.car > img {
				@media only screen and (min-width: 992px) {
					max-width: 200px;
				}
			}
		}
	}
</style>
