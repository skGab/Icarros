<script lang="ts">
	import arrow_right from '$lib/icons/arrow-right.png';
	import cta_logo from '$lib/images/cta-logo.webp';
	import cta_lupa from '$lib/icons/lupa-cta.svg';
	import cta_img from '$lib/images/cta-img.webp';
</script>

<div class="card py-3">
	<div class="card-body text-center">
		<figure>
			<img loading="lazy" src={cta_logo} class="img-fluid" alt="Icarros Logo" />
		</figure>
		<p class="card-text fw-bold text-white border border-2 rounded-top  mx-auto p-3">
			por aqui você faz tudo: <br />
			compra, vende e financia
		</p>
		<figure>
			<img loading="lazy" src={cta_img} class="img-fluid" alt="Imagem CTA" />
		</figure>
		<a
			href="/"
			class="btn fw-bold px-4 py-2"
			data-aos="fade-left"
			data-aos-placement="top-bottom"
			data-aos-duration="950"
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

<style lang="scss">
	@mixin animation($bg-color) {
		background-color: $bg-color;
		transition: all 0.5s ease;
	}

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
</style>
