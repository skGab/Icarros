<script lang="ts">
	import { Splide, SplideSlide } from '@splidejs/svelte-splide';
	import arrow_right from '$lib/icons/arrow-right.png';
	import sell_icon from '$lib/icons/sell-icon.png';
	import service_icon from '$lib/icons/service-icon.png';
	import finance_icon from '$lib/icons/finance-icon.png';
</script>

<Splide
	id="services_slide"
	options={{
		arrows: true,
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
					<img loading="lazy" src={service_icon} class="img-fluid mb-4" alt="Icone Serviço" />
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
					<img loading="lazy" src={finance_icon} class="img-fluid mb-4" alt="Icone Finanças" />
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
							<h4 class="card-tex text-secondary small">opções de financiamento e simulações</h4>
						</div>
						<img src={arrow_right} class="img-fluid" alt="Seta para direita" />
					</div>
				</div>
			</a>
		</div>
	</SplideSlide>
</Splide>

<style lang="scss">
	a:hover h3 {
		transition: all 0.2s ease-in;
		color: var(--laranja-claro) !important;
	}
</style>
