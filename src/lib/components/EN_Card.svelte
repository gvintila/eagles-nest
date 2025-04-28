<script>
    let { src, title, text } = $props();
    import { Card } from 'flowbite-svelte';
</script>
  
<Card class="bg-site-fill my-16 h-88 max-w-112 rounded-4xl border-none drop-shadow-md drop-shadow-trackman-300">
    <img src={src} class="mx-auto mt-4 h-auto w-32" alt="Card Icon" />
    <h3>{title}</h3>
    <p>{text}</p>
</Card>