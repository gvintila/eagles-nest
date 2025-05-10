<svelte:head>
    <title>How It Works | Eagle's Nest</title>
    <meta tag="description"
    content="Joining is simple: choose a membership, book through Trackman, get your access PIN, and enjoy 24/7 golf in a secure, staff-free private facility.">
</svelte:head>

<script>
    import ArrowDownOutline from 'flowbite-svelte-icons/ArrowDownOutline.svelte';
    import { Card } from 'flowbite-svelte';

    // Card Images
    import card_membership from "$lib/images/howitworks/membership.png";
    import card_booking from "$lib/images/howitworks/booking.png";
    import card_password from "$lib/images/howitworks/password.png";
    import card_golfclub from "$lib/images/howitworks/golf_club.png";
</script>

<h2>How It Works</h2>

<!-- Step-by-Step Breakdown -->
<div class="grid grid-cols-1 columns-lg justify-items-center mx-8 sm:mx-auto mt-24 sm:mt-32 sm:w-lg">
    <Card class="en-card pb-8 sm:min-w-md">
        <img src={card_membership} class="mx-auto mt-4 h-auto w-16 sm:w-24" alt="Card Icon" />
        <p>Choose a membership that fits your playing needs</p>
    </Card>
    <ArrowDownOutline color="white" class="size-30" />
    <Card class="en-card pb-8 sm:min-w-md">
        <img src={card_booking} class="mx-auto mt-4 h-auto w-16 sm:w-24" alt="Card Icon" />
        <p>Book your bay through Trackman</p>
    </Card>
    <ArrowDownOutline color="white" class="size-30" />
    <Card class="en-card pb-8 sm:min-w-md">
        <img src={card_password} class="mx-auto mt-4 h-auto w-16 sm:w-24" alt="Card Icon" />
        <p>Receive a PIN to enter—no staff, no wait</p>
    </Card>
    <ArrowDownOutline color="white" class="size-30" />
    <Card class="en-card pb-8 sm:min-w-md">
        <img src={card_golfclub} class="mx-auto mt-4 h-auto w-16 sm:w-24" alt="Card Icon" />
        <p>Play at your scheduled time—solo or with guests</p>
    </Card>
</div>