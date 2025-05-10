<script>
    import ImgTextCombo from "$lib/components/ImgTextCombo.svelte";

    // Images
    import pdark_img from "$lib/images/about/player_dark.jpg";
    import pswing_img from "$lib/images/about/player_swing.jpg";
</script>

<h2 class="mt-32 text-5xl sm:text-7xl">About Us</h2>

<div class="mt-16 sm:mt-24"></div>
<ImgTextCombo src={pdark_img} title="What Makes Us Different" 
text="Our indoor golf studio offers a fully automated, member-exclusive experience unlike anything else. Powered by industry-leading Trackman simulators, members enjoy 24/7 access to a private, high-end space tailored for convenience and performance. With no staff and seamless self-check-in, you're free to practice, play, and unwind on your schedule." 
rev=0 ext="left" />
<ImgTextCombo src={pswing_img} title="Our Vision" 
text="We aim to redefine the way golfers train and play by delivering a consistent, premium experience every time. Through a fully automated, member-only model, we remove the friction of traditional facilities and focus on what matters most: quality, privacy, and performance. With 24/7 access to world-class Trackman technology in a clean, secure environment, our vision is to create a space where excellence is always within reach—anytime you choose to play." 
rev=1 ext="left" />