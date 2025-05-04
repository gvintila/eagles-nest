<script>
    import ImgTextCombo from "$lib/components/ImgTextCombo.svelte";
    import automation_img from "$lib/images/facility/automation-stock.jpg";
</script>

<div class="h-160 w-[40%] absolute left-1/2 transform -translate-x-1/2 -top-96 -z-1">
    <div class="size-full rounded-full bg-radial from-gray-500 to-transparent blur-3xl"></div>
</div>
<h2 class="mt-32 text-5xl sm:text-7xl">Facility</h2>

<ImgTextCombo src={automation_img} title="Secure PIN Codes" 
text="Before each booking, you will be provided a secure PIN code..." />