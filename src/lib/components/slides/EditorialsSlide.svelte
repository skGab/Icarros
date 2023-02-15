<script lang="ts">
	import { Splide, SplideSlide } from '@splidejs/svelte-splide';
	import arrow_right from '$lib/icons/arrow-right.png';
	import place from '$lib/icons/place.png';
	import bussiness_icon from '$lib/icons/bussiness-icon.png';
	import manuntance_icon from '$lib/icons/manuntance-icon.png';
	import insuranceAuto from '$lib/icons/insuranceAuto.png';
	import web_icon from '$lib/icons/web-icon.png';
	import person_icon from '$lib/icons/person-icon.png';
</script>

<Splide
	id="editorials_slide"
	options={{
		gap: '2rem',
		arrows: true,
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
	class="splide"
>
	<SplideSlide class="splide__slide">
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

	<SplideSlide class="splide__slide">
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
	</SplideSlide>

	<SplideSlide class="splide__slide">
		<div class="card w-100 h-100 p-2">
			<a href="/" class="card-body">
				<img loading="lazy" src={manuntance_icon} class="img-fluid mb-5" alt="Icone Manutenção" />
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

	<SplideSlide class="splide__slide">
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

	<SplideSlide class="splide__slide">
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
	</SplideSlide>

	<SplideSlide class="splide__slide">
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

<style lang="scss">
	.card {
		border: #00000025 solid 1px;
		border-radius: 12px;

		letter-spacing: 0.1px;
	}

	a:hover {
			h3 {
				transition: all 0.2s ease-in;
				color: var(--laranja-claro) !important;
			}
		}
</style>
