<script>
    import { AccordionItem, Accordion } from "flowbite-svelte";
</script>

<div class="h-160 w-[40%] absolute left-1/2 transform -translate-x-1/2 -top-96 -z-1">
    <div class="size-full rounded-full bg-radial from-gray-500 to-transparent blur-3xl"></div>
</div>
<h2 class="mt-32 text-5xl sm:text-7xl">FAQ</h2>

<Accordion multiple class="mt-16 sm:mt-24 mx-4 xl:mx-[15vw]">
    <AccordionItem borderSharedClass="border-gray-700 border-1" tag="h6" class="dark dark:text-white-2">
        {#snippet header()}Can I bring guests?{/snippet}
        <p class="text-left text-white-2">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo ab necessitatibus sint explicabo ...</p>
    </AccordionItem>
    <AccordionItem borderSharedClass="border-gray-700 border-1" tag="h6" class="dark dark:text-white-2">
        {#snippet header()}Can I cancel or extend sessions?{/snippet}
        <p class="text-left text-white-2">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo ab necessitatibus sint explicabo ...</p>
    </AccordionItem>
    <AccordionItem borderSharedClass="border-gray-700 border-1" tag="h6" class="dark dark:text-white-2">
        {#snippet header()}How secure is the facility?{/snippet}
        <p class="text-left text-white-2">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo ab necessitatibus sint explicabo ...</p>
    </AccordionItem>
    <AccordionItem borderSharedClass="border-gray-700 border-1" tag="h6" class="dark dark:text-white-2">
        {#snippet header()}What's the best membership for me?{/snippet}
        <p class="text-left text-white-2">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo ab necessitatibus sint explicabo ...</p>
    </AccordionItem>
</Accordion>
