<svelte:head>
    <title>FAQ | Eagle's Nest</title>
    <meta tag="description"
    content="Find answers to common questions about memberships, access, technology, and what makes our indoor golf experience unique.">
</svelte:head>

<script>
    import { AccordionItem, Accordion } from "flowbite-svelte";
</script>

<h2>FAQ</h2>

<Accordion multiple class="mt-24 sm:mt-32 mx-4 xl:mx-[20vw]">
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
