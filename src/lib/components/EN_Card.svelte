<!-- This component is used for displaying features regarding a section of the business with a compatible icon and short description -->

<!-- src - Source for image -->
<!-- title - Title of card  -->
<!-- text - Paragraph under title for card -->

<script>
    let { src, title, text } = $props();
    import { Card } from 'flowbite-svelte';
</script>
  
<Card class="en-card mt-12 sm:mt-16 h-76 sm:h-88 max-w-112">
    <img src={src} class="mx-auto mt-4 h-auto w-24 sm:w-32" alt="Card Icon" />
    <h3>{title}</h3>
    <p>{text}</p>
</Card>