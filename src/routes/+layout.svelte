<script>
	import Header from '../lib/header.svelte';
	import Footer from '../lib/footer.svelte';
	import '../global.scss';
</script>

<div class="app">
	<Header />

	<main>
		<slot />
	</main>

	<Footer />
</div>

<style>

</style>
