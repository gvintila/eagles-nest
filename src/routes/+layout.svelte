<script>
	import '../app.css';
	import '@fontsource-variable/oswald';
	import '@fontsource-variable/roboto-flex';
	import Nav from '$lib/components/Nav.svelte';
	let { children } = $props();
</script>

<Nav />

{@render children()}
