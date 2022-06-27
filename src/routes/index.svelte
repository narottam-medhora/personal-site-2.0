<!-- Inject CSS reset into <head> -->
<svelte:head>
    <!-- Stylesheets -->
    <link rel="stylesheet" href="./src/styles/reset.css">
    <link rel="stylesheet" href="./src/styles/global.css">

    <!-- Favicons -->
    <link rel="apple-touch-icon" sizes="180x180" href="./static/favicons/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="./static/favicons/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="./static/favicons/favicon-16x16.png">
    <link rel="manifest" href="site.webmanifest">
</svelte:head>

<!-- Import components -->
<script>
    import Placeholder from "../components/Placeholder.svelte";
    import Footer from "../components/Footer.svelte";
</script>

<!-- Place components -->
<Placeholder />
<Footer />

