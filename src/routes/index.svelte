<script>
    let text = 'Lorem Ipsum Text Generator';
    
    const changeTitle = () =>
    {
        text = 'random text generator';
    }
</script>

<div class="index">

    <h1>{text}</h1>
    <p>
        Lorem Ipsum is simply dummy text of the printing and typesetting industry.
        Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, 
        when an unknown printer took a galley of type and scrambled it to make a type specimen book. 
        It has survived not only five centuries, but also the leap into electronic typesetting,
        remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset 
        sheets containing Lorem Ipsum passages,and more recently with desktop publishing software like
        Aldus PageMaker including versions of Lorem Ipsum.

        It is a long established fact that a reader will be distracted by the readable content of a page
        when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal
        distribution of letters, as opposed to using 'Content here, content here',
        making it look like readable English. Many desktop publishing packages and web page editors now use
        Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites
        still in their infancy. Various versions have evolved over the years,
        sometimes by accident, sometimes on purpose (injected humour and the like).
    </p>

    <button on:click={changeTitle}>Click me to change the title</button>
    <input type="text" bind:value={text}>

    <a href="/guides">View Guides</a>
    <a href="/about">View About Page</a>


</div>

<style>

    .index
    {
        display:block;
        margin:20px auto;
        text-align:center;
    }

    a{
        display:inline-block;
        margin-top: 10px;
        padding:10px;
        border: 1px dotted red;
    }


</style>
