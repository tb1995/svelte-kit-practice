<script>
    import Title from '../../lib/title.svelte'
    import '../../styles/global.css'
</script>

<style>
  header
 {
     justify-content:center;
     background:rgba(0,0,0,0.1);
 }

 main
 {
     max-width:960px;
     margin:20px auto;

 }

 footer{

     text-align:center;
 }

 .links
 {
  margin-left: auto;
 }

 a{
  margin-left: 10px;
 }

nav
{
    display:flex;
    align-items:center;
    max-width:960px;
    margin:0 auto;
}
</style>

<header>
  <nav> <Title title="Reusable Components (Lesson 5)"/>
    <div class="links">
       <a href="/">Home</a>
       <a href="/about">About</a>
       <a href="/guides">Guides</a>
    </div></nav>
</header>

<main>
 <!--page content will show here-->
 <slot>
 </slot>
</main>

<footer>
 Copyright 2022
</footer>

