<svelte:head>
    <title>Facility | Eagle's Nest</title>
    <meta tag="description"
    content="Step inside a secure, private indoor golf facility with 24/7 member access—featuring Trackman simulators and premium technology for a refined experience.">
</svelte:head>

<script>
    import { Lightbox } from 'svelte-lightbox';
    import Subheader from '$lib/components/Subheader.svelte';
    import EN_Card from '$lib/components/EN_Card.svelte';
    import ImgTextCombo from "$lib/components/ImgTextCombo.svelte";

    // Gallery Images
    import gal_stock_1 from "$lib/images/facility/gallery/zenswingstage_01_72dpi_web.jpg";
    
    // Card Images
    import card_monitor from "$lib/images/facility/cards/monitor.png";
    import card_tv from "$lib/images/facility/cards/television.png";
    import card_speaker from "$lib/images/facility/cards/speaker.png";
    import card_mat from "$lib/images/facility/cards/yoga-mat.png";
    
    // Other Images
    import pincode_img from "$lib/images/facility/pincode.jpg";
    import power_img from "$lib/images/facility/power.jpg";
    import camera_img from "$lib/images/facility/camera.jpg";
</script>

<h2>Facility</h2>

<!-- Gallery Section -->
<div class="flex flex-wrap gap-12 sm:gap-16 justify-center mt-24 sm:mt-32 mx-8 sm:mx-16 2xl:mx-64">
    <Lightbox>
        <img class="w-xs rounded-4xl drop-shadow-md drop-shadow-trackman-300" src={gal_stock_1} alt="Gallery thumbnail">
    </Lightbox>
    <Lightbox>
        <img class="w-xs rounded-4xl drop-shadow-md drop-shadow-trackman-300" src={gal_stock_1} alt="Gallery thumbnail">
    </Lightbox>
    <Lightbox>
        <img class="w-xs rounded-4xl drop-shadow-md drop-shadow-trackman-300" src={pincode_img} alt="Gallery thumbnail">
    </Lightbox>
    <Lightbox>
        <img class="w-xs rounded-4xl drop-shadow-md drop-shadow-trackman-300" src={gal_stock_1} alt="Gallery thumbnail">
    </Lightbox>
    <Lightbox>
        <img class="w-xs rounded-4xl drop-shadow-md drop-shadow-trackman-300" src={pincode_img} alt="Gallery thumbnail">
    </Lightbox>
    <Lightbox>
        <img class="w-xs rounded-4xl drop-shadow-md drop-shadow-trackman-300" src={gal_stock_1} alt="Gallery thumbnail">
    </Lightbox>
</div>

<!-- Card Section -->
<Subheader title="Bay Features" />
<div class="flex flex-wrap gap-x-16 justify-center mt-4 sm:mt-8 mx-8 sm:mx-16 2xl:mx-[15vw]">
    <EN_Card src={card_monitor} title="Trackman Launch Monitors" 
    text="Trackman launch monitors deliver precise, data-driven insights to help you analyze every shot and elevate your performance." />
    <EN_Card src={card_tv} title="Smart TVs" 
    text="Enjoy using our large Smart TVs for streaming entertainment, watching sports, or displaying swing data—perfect for relaxing or dialing in your game." />
    <EN_Card src={card_speaker} title="Bluetooth Sound Systems" 
    text="Enjoy rich, high-quality sound with premium Bluetooth systems that deliver crystal-clear audio and deep, balanced tones." />
    <EN_Card src={card_mat} title="Custom Turf and Mats" 
    text="Experience realistic play and consistent feel with our custom-made turf and hitting mats designed to replicate on-course conditions." />
</div>

<!-- About Facility  -->
<Subheader title="Automation & Access" />
<div class="mt-16 sm:mt-24">
    <ImgTextCombo src={pincode_img} title="Secure PIN Codes" 
    text="For each booking, you will be provided a secure PIN code that you can use to check in 15 minutes before your alloted time." 
    rev=0 />
    <ImgTextCombo src={power_img} title="Automatic Power Down" 
    text="Once the booked session is over, all technological equipment will be automatically shut down." 
    rev=1 />
    <ImgTextCombo src={camera_img} title="Security Cameras" 
    text="Security cameras will be utilized to maintain security and logging entries for each booking member." 
    rev=0 />
</div>