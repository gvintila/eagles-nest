<!-- Any images used in the body of the webpage will be imported in the script section below -->
<script>
    import { Button } from 'flowbite-svelte';
    import EN_Card from '$lib/components/EN_Card.svelte';
    import powered_tm from '$lib/images/TrackMan_Powered By_White.png';
    import hero_img from '$lib/images/home/stock-1.jpg';
    import card_golfclub from '$lib/images/home/golf_club.png';
    import card_24_7 from '$lib/images/home/24-7.png';
    import card_broom from '$lib/images/home/broom.png';
</script>

<!-- Hero Section -->

<!-- This div displays the blurry gray dot in the background -->
<div class="h-160 w-[40%] absolute left-1/2 transform -translate-x-1/2 -top-96 -z-1">
    <div class="size-full rounded-full bg-radial from-gray-500 to-transparent blur-3xl"></div>
</div>

<h1>PREMIUM 24/7 INDOOR GOLF</h1>
<img src={powered_tm} class="mx-auto w-[16rem] sm:w-3xs" alt="Powered by TrackMan"/>
<div class="flex justify-center gap-x-4 mt-2">
    <Button pill class="text-xs sm:text-sm bg-trackman-100 hover:bg-trackman-200 w-40 sm:w-50" href="/membership">Explore Memberships</Button>
    <Button pill class="text-xs sm:text-sm bg-trackman-100 hover:bg-trackman-200 w-40 sm:w-50" href="/facility">Take a Tour</Button>
</div>
<img src={hero_img} class="mt-8 sm:mt-16 h-auto w-full border-y border-nav-stroke" alt="Man playing TrackMan golf" />

<!-- Card Section -->

<h2>What We Offer</h2>
<div class="flex flex-wrap gap-x-16 justify-center sm:mt-8 mx-8 sm:mx-16 2xl:mx-64">
    <EN_Card src={card_golfclub} title="Trackman Simulators" 
    text="Experience the best indoor golfing technology with Trackman&#39s state-of-the-art golf simulators." />
    <EN_Card src={card_24_7} title="Convenient Access" 
    text="Our facility offers 24/7 access with no staff, 
    giving you the freedom to play on your schedule in total privacy and comfort." />
    <EN_Card src={card_broom} title="Clean Comfort" 
    text="Enjoy a clean, tech-driven, and fully private space designed for a seamless, elevated golfing experience." />
</div>