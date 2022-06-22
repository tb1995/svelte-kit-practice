<script>
       import Title from '../lib/title.svelte'
       import '../styles/global.css'
</script>

<style>

    header
    {
        display:flex;
        justify-content:center;
    }

    main
    {
        max-width:960px;
        margin:20px auto;

    }

    footer{

        text-align:center;
    }
</style>

<header>
    <Title title="Reusable Components (Lesson 5)"/>
</header>

<main>
    <!--page content will show here-->
    <slot>
    </slot>
</main>

<footer>
    Copyright 2022
</footer>


