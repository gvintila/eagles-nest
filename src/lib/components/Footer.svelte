<script>
    import en_logo from '$lib/images/en_logo.png';
</script>

<div class="z-10">
    <div class="bg-site-fill border-t border-nav-stroke grid grid-cols-3 sm:grid-cols-4 lg:grid-cols-7 justify-items-center items-center gap-x-4 sm:gap-x-[2vw] mt-48 pt-12 sm:pt-4 w-full h-72 sm:h-48">
        <img src={en_logo} class="col-span-3 sm:col-span-1 lg:col-span-2 sm:ml-2 h-16" alt="Eagle's Nest" />
        
        <div class="flex flex-col h-40 min-w-min justify-center items-center">
            <small>Address</small>
            <div class="flex flex-col h-20 min-w-min">
                <small class="font-light text-xs sm:text-sm">123 Street Ave</small>
            </div>
        </div>

        <div class="flex flex-col h-40 min-w-min justify-center items-center">
            <small>Contact</small>
            <div class="flex flex-col h-20 min-w-min">
                <small class="font-light text-xs sm:text-sm">123-456-7890</small>
                <small class="font-light text-xs sm:text-sm">email@gmail.com</small>
            </div>
        </div>

        <div class="flex flex-col h-40 min-w-min justify-center items-center">
            <small>Socials</small>
            <div class="flex flex-col h-20 min-w-min">
                <small class="font-light text-xs sm:text-sm">?</small>
            </div>
        </div>

        <img src={en_logo} class="hidden lg:block invisible col-span-2 ml-2 h-16" alt="" />
    </div>

    <small class="block font-light text-gray-400 text-xs sm:text-sm mb-4">Made with Flaticon icons</small>
</div>