<script>
    import { Button } from 'flowbite-svelte';
    import EN_Card from '$lib/components/EN_Card.svelte';
    import powered_tm from '$lib/images/TrackMan_Powered By_White.png';
    import hero_img from '$lib/images/home/stock-1.jpg';
    import monitor from '$lib/images/home/monitor.png';
</script>

<!-- Hero Section -->

<div class="absolute left-1/2 transform -translate-x-1/2 -top-96 -z-1">
    <div class="size-160 rounded-full bg-radial from-gray-500 to-transparent blur-3xl"></div>
</div>
<h1>PREMIUM 24/7 INDOOR GOLF</h1>
<img src={powered_tm} class="mx-auto w-3xs" alt="Powered by TrackMan"/>
<div class="flex justify-center space-x-4 mt-2">
    <Button pill class="bg-trackman-100 hover:bg-trackman-200 w-50" href="/membership">Explore Memberships</Button>
    <Button pill class="bg-trackman-100 hover:bg-trackman-200 w-50" href="/facility">Take a Tour</Button>
</div>
<img src={hero_img} class="mt-16 h-auto w-full border-y border-nav-stroke" alt="Man playing TrackMan golf" />

<!-- Card Section -->

<h2>What We Offer</h2>
<EN_Card src={monitor} title="Trackman Launch Monitors" 
text="Trackman launch monitors deliver precise, data-driven insights
 to help you analyze every shot and elevate your performance." />