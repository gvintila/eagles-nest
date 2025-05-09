<script>
    import EN_Card from '$lib/components/EN_Card.svelte';
    import ImgTextCombo from "$lib/components/ImgTextCombo.svelte";

    // Other Images
    import pincode_img from "$lib/images/facility/pincode.jpg";
    import power_img from "$lib/images/facility/power.jpg";
    import camera_img from "$lib/images/facility/camera.jpg";
</script>

<div class="h-160 w-[40%] absolute left-1/2 transform -translate-x-1/2 -top-96 -z-1">
    <div class="size-full rounded-full bg-radial from-gray-500 to-transparent blur-3xl"></div>
</div>
<h2 class="mt-32 text-5xl sm:text-7xl">How It Works</h2>

<h2>Automation & Access</h2>
<ImgTextCombo src={pincode_img} title="Secure PIN Codes" 
text="For each booking, you will be provided a secure PIN code that you can use to check in 15 minutes before your alloted time." 
rev=0 />
<ImgTextCombo src={power_img} title="Automatic Power Down" 
text="Once the booked session is over, all technological equipment will be automatically shut down." 
rev=1 />
<ImgTextCombo src={camera_img} title="Security Cameras" 
text="Security cameras will be utilized to maintain security and logging entries for each booking member." 
rev=0 />