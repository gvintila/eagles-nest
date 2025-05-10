<!-- This component will represent a subheader with a blurry gray dot -->

<!-- title - Title of subheader  -->

<script>
    let { title } = $props();
</script>

<div class="relative">
    <!-- This div displays the blurry gray dot in the background -->
    <div class="h-100 w-[40%] absolute left-1/2 transform -translate-x-1/2 -top-76 -z-10">
        <div class="size-full rounded-full subheader-gradient blur-2xl"></div>
    </div>
    <h2 class="mt-16 sm:mt-32 text-4xl sm:text-6xl">{title}</h2>
</div>