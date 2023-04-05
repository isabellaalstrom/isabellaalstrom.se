<script>
    import Header from "../lib/components/Header.svelte";
    import "@fontsource/montserrat-subrayada";
    import "@fontsource/libre-baskerville";
    import "@fontsource/montserrat";
</script>
<Header />
<div class="app-container">
    <slot>

    </slot>
</div>

<style>
    .app-container{
        display: flex;
        flex-direction: column;
        /* align-items: center; */
        /* justify-content: center;  */
        height: 100%;
        margin: 2rem;
    }
</style>