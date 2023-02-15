<script>
	import Header from '$lib/components/Header.svelte';
	import Footer from '$lib/components/Footer.svelte';
	import CDN from '$lib/components/Cdn.svelte';
	import '../global.scss';
</script>

<CDN />

<div>
	<Header />

	<main>
		<slot />
	</main>

	<Footer />
</div>