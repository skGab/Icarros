<script>
	import arrow_right_white from '$lib/icons/arrow-right-white.png';
</script>

<div class="card p-2">
	<div class="card-body text-white d-flex flex-column justify-content-between">
		<span class="border border-1 border-white rounded-3 px-2">lorem ipsum</span>
		<div>
			<h3 class="card-text h6 lh-base">
				icarros aponta aumento de 500% na busca por híbridos nos últimos meses
			</h3>
			<button class="btn p-0">
				<a href="/" class="h6"
					>ver matéria
					<img loading="lazy" src={arrow_right_white} class="img-fluid" alt="Icone seta direita" />
				</a>
			</button>
		</div>
	</div>
</div>

<style lang="scss">
	.card {
		background: url('../images/card-bg.webp') center no-repeat;
		background-size: cover;
		min-height: 320px;
		border: none;
		border-radius: 12px;
		letter-spacing: 0.1px;
	}
</style>
