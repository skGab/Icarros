<script>
	import Header from '$lib/header.svelte';
	import Footer from '$lib/footer.svelte';
	import Cdn from '$lib/cdn.svelte';
	import '../global.scss';
</script>

<Cdn />

<div class="app">
	<Header />

	<main>
		<slot />
	</main>

	<Footer />
</div>

<style>
</style>
