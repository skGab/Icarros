<script lang="ts">
	import { Splide, SplideSlide } from '@splidejs/svelte-splide';
</script>

<Splide
	id="gallery_slide"
	options={{
		arrows: true,
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

<style lang="scss">
	.card {
		background: url('../../../lib/images/gallery-img.webp') center no-repeat;
		background-size: cover;
		min-height: 385px;
		cursor: pointer;
		border-radius: 20px;
		letter-spacing: 0.1px;
	}
</style>
