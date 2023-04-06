<script>
    import './../lib/keyframes.css';
    import Intro from "../lib/components/Intro.svelte";
    import Name from "../lib/components/Name.svelte";
    import Cv from '../lib/components/Cv.svelte';
    import Contact from '../lib/components/Contact.svelte';
</script>
<section class="logo">
    <Name />
</section>
<section class="information">
    <Intro/>
    <Cv/>
    <Contact/>
</section>
