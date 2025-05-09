<script>
    import { Button, Card } from 'flowbite-svelte';
</script>

<!-- Title -->

<div class="h-160 w-[40%] absolute left-1/2 transform -translate-x-1/2 -top-96 -z-1">
    <div class="size-full rounded-full bg-radial from-gray-500 to-transparent blur-3xl"></div>
</div>
<h2 class="mt-32 text-5xl sm:text-7xl">Membership</h2>

<!-- Membership Card Section -->

<div class="flex flex-wrap gap-x-16 justify-center mt-16 sm:mt-24 mx-8 sm:mx-16 2xl:mx-64">
    <Card class="bg-site-fill mt-12 sm:mt-16 pb-8 h-fit sm:h-96 max-w-112 rounded-4xl border-none drop-shadow-md drop-shadow-trackman-300">
        <h3 class="text-5xl sm:text-5xl">Birdie</h3>
        <div class="text-center mt-4">
            <h3 class="inline text-5xl sm:text-5xl text-trackman-100">$249</h3>
            <small class="inline">/month</small>
            <br>
            <small>($30 hourly rate)</small>
        </div>
        <ul class="font-secondary text-white-2 text-lg list-disc mt-8 mx-8">
            <li><b>24/7</b> PIN access</li>
            <li><b>8</b> hours of simulator access monthly</li>
            <li>Book up to <b>2</b> days in advance</li>
            <li>Bring up to <b>3</b> guests*</li>
        </ul>
    </Card>
    <Card class="bg-site-fill mt-12 sm:mt-16 pb-8 h-fit sm:h-96 max-w-112 rounded-4xl border-none drop-shadow-md drop-shadow-trackman-300">
        <h3 class="text-5xl sm:text-5xl">Eagle</h3>
        <div class="text-center mt-4">
            <h3 class="inline text-5xl sm:text-5xl text-trackman-100">$349</h3>
            <small class="inline">/month</small>
            <br>
            <small>($25 hourly rate)</small>
        </div>
        <ul class="font-secondary text-white-2 text-lg list-disc mt-8 mx-8">
            <li><b>24/7</b> PIN access</li>
            <li><b>14</b> hours of simulator access monthly</li>
            <li>Book up to <b>4</b> days in advance</li>
            <li>Bring up to <b>3</b> guests* (first guest is <b>free!</b>)</li>
        </ul>
    </Card>
</div>

<p class="mt-8 px-8">*$5 must be paid for each guest except for the first guest with the Eagle membership</p>
<p class="mt-8 px-8">All bookings are hourly and <b>require</b> reservation in advance!</p>

<!-- Membership CTA -->

<div class="flex justify-center gap-x-4 mt-16">
    <Button pill class="text-xs sm:text-sm bg-trackman-100 hover:bg-trackman-200 w-40 sm:w-50" href="https://www.trackman.com/">Join Eagle's Nest</Button>
</div>