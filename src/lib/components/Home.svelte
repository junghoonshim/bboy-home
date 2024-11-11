<script>
    import Footer from "./Footer.svelte";
    import Header from "./Header.svelte";
</script>
<Header />
<main class="container">
    <img src="/images/MIZZ.jpg" alt="임미쯔">
</main>
<Footer />
<style>
    img {
        width: 100%;

        object-fit: cover;
        object-position: center;
        display: block;
    }
</style>