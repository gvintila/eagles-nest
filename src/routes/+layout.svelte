<script>
	import '../app.css';
	import '@fontsource-variable/oswald';
	import '@fontsource-variable/roboto';
	import Nav from '$lib/components/Nav.svelte';
	import Footer from '$lib/components/Footer.svelte';
	let { children } = $props();
</script>

<Nav />

{@render children()}

<Footer />
