<script>
    import '../styles/global.css'
    //import Title from ' $lib/titlee.svelte '
</script>
<header>
    <!-- <Title  title="Learning Svelte kit" /> -->
</header>
<main>
    <slot></slot>
</main>
<footer>
    copyright 2022
</footer>

<style>
    header
    {
     display: flex;
     justify-content: center;
    }

    footer
    {
     text-align: center;
    }

    main
    {
        max-width: 960px;
        margin: 20px auto;
    }
</style>