<!-- This component will represent a collapsible image text side-by-side used in several parts of the website -->

<!-- src - Source for image -->
<!-- title - Title of text section  -->
<!-- text - Paragraph of text section -->
<!-- rev - indicates if image / text should be reversed (swapped) -->

<script>
    let { src, title, text, rev = 0 } = $props();
</script>
  
<!-- Non-reversed -->
{#if rev == 0}
    <div class="grid grid-cols-2 gap-16 justify-center justify-items-center mt-8 xl:mt-16 mx-[5vw] xl:mx-[15vw]">
        <!-- Text Section -->
        <div class="col-span-2 xl:col-span-1 px-[3vw] sm:w-lg xl:w-full">
            <h3>{title}</h3>
            <p class="text-center">{text}</p>
        </div>
        <!-- Image Section -->
        <img class="col-span-2 xl:col-span-1 min-w-2xs w-[50vw] xl:w-[75%]" src={src} alt="{title} image" />
    </div> 
<!-- Reversed -->
{:else}
    <div class="grid grid-cols-2 gap-16 justify-center justify-items-center mt-8 xl:mt-16 mx-[5vw] xl:mx-[15vw]">
        <!-- Image Section -->
        <img class="row-2 xl:row-1 col-span-2 xl:col-span-1 min-w-2xs w-[50vw] xl:w-[75%]" src={src} alt="{title} image" />
        <!-- Text Section -->
        <div class="row-1 xl:row-1 col-span-2 xl:col-span-1 px-[3vw] sm:w-lg xl:w-full">
            <h3>{title}</h3>
            <p class="text-center">{text}</p>
        </div>
    </div> 
{/if}