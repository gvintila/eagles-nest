<script>
	import '../app.css';
	import '@fontsource-variable/oswald';
	import '@fontsource-variable/roboto';
	import Nav from '$lib/components/Nav.svelte';
	import Footer from '$lib/components/Footer.svelte';
	let { children } = $props();
</script>

<Nav />

<!-- This div displays the blurry gray dot in the background -->
<div class="h-160 w-[40%] absolute left-1/2 transform -translate-x-1/2 -top-100 -z-1">
    <div class="size-full rounded-full bg-radial from-neutral-700 to-transparent blur-3xl"></div>
</div>

{@render children()}

<Footer />
