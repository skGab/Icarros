<script>
	import Header from '$lib/components/header.svelte';
	import Footer from '$lib/components/footer.svelte';
	import Cdn from '$lib/components/cdn.svelte';
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
