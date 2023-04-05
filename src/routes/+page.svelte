<script>
    import Saos from "saos";
    import './../lib/keyframes.css';
    import Intro from "../lib/components/Intro.svelte";
    import Name from "../lib/components/Name.svelte";
</script>
<div class="name">
    <Name />
</div>
    <Saos animation={"fade-in-bottom 0.6s cubic-bezier(0.390, 0.575, 0.565, 1.000) both"}>
        <Intro/>
    </Saos>

<style>
    /* .name {
        display: flex;
        align-items: center;
        justify-content: center;
    } */
</style>