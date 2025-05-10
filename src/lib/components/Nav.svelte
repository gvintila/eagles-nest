<!-- This component represents the top navigation bar that will be accessed from every page of the website -->

<script>
    import { page } from '$app/state'
    import { Navbar, NavBrand, NavLi, NavUl, NavHamburger, Button, Input } from 'flowbite-svelte';
    import { sineIn } from "svelte/easing";
    import en_logo from '$lib/images/en_logo.png';
    let slideParams = { delay: 50, duration: 350, easing: sineIn };
    let activeUrl = $derived(page.url.pathname);
    let activeClass = 'text-trackman-100';
    let nonActiveClass = 'dark:text-white-1 hover:text-trackman-100';
</script>
  
<div class="relative">
    <Navbar fluid="true" class="w-full fixed -top-0 start-0 z-20 bg-nav-fill border-b-1 border-nav-stroke" navContainerClass="xl:px-[7.5vw]">
        <NavBrand href="/">
            <img src={en_logo} class="h-[48px] p-1" alt="Eagle's Nest" />
        </NavBrand>
        <div class="flex md:order-2">
            <Button pill size="sm" class="animate-button text-xs sm:text-sm bg-trackman-100">Book Now</Button>
            <NavHamburger class="hover:bg-site-fill"/>
        </div>
        <NavUl class="order-1 dark" classUl="bg-site-fill" {slideParams} {activeUrl} {activeClass} {nonActiveClass}>
            <NavLi href="/" active={true}>Home</NavLi>
            <NavLi href="/about">About</NavLi>
            <NavLi href="/facility">Facility</NavLi>
            <NavLi href="/membership">Membership</NavLi>
            <NavLi href="/howitworks">How It Works</NavLi>
            <NavLi href="/faq">FAQ</NavLi>
        </NavUl>
    </Navbar>
</div>