<script lang="ts"></script>

<svelte:head />

<style lang="scss">
	@mixin shadowEffect() {
		transition: all 0.2s ease-in;
		filter: drop-shadow(1px 2px 4px rgba(0, 0, 0, 0.541));
	}

	@mixin animation($bg-color) {
		background-color: $bg-color;
		transition: all 0.5s ease;
	}
	#banner_hero {
		min-height: 498px;
		background: url('/src/lib/images/banner_hero.webp') center no-repeat;
		background-size: cover;
		@media screen and (min-width: 992px) {
			width: fit-content;
			margin: 5rem auto;
			border-radius: 15px;
		}
	}

	#social {
		figure img:hover {
			@include shadowEffect();
		}
	}

	#editorials_single {
		li {
			background-color: var(--laranja-claro);
			border-radius: 10px;
		}

		li:hover {
			@include animation(var(--preto));
		}
	}
</style>
