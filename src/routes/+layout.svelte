<script>
    import "../app.css";
    import NavBar from '$lib/components/NavBar.svelte';
    import Footer from "./Footer.svelte";
</script>

<NavBar />

<slot />

<Footer />