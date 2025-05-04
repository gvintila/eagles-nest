<!-- This component will represent a collapsible image text side-by-side used in several parts of the website -->

<script>
    let { src, title, text } = $props();
</script>
  
<div class="grid grid-cols-2 gap-x-16 gap-y-16 justify-center mt-8 xl:mt-16 mx-[10vw]">
    <!-- Text Section -->
    <div class="col-span-2 xl:col-span-1">
        <h3>{title}</h3>
        <p>{text}</p>
    </div>
    <!-- Image Section -->
    <img class="col-span-2 xl:col-span-1" src={src} alt="{title} image" />
</div> 