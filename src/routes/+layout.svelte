<script>
    import Header from "../lib/components/Header.svelte";
    import Footer from "../lib/components/Footer.svelte";
    import "@fontsource/montserrat-subrayada";
    import "@fontsource/libre-baskerville";
    import "@fontsource/montserrat";
</script>
<div class="app-container">
<Header />
    <slot></slot>
    <Footer/>
</div>
<style>
    .app-container{
        display: flex;
        flex-direction: column;
        margin: 2rem 20rem;
    }
    @media screen and (max-width: 992px) {
        .app-container {
            margin: 2rem;
            width: unset;
        }
    }
</style>