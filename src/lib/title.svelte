<script>
    export let title = "Reusable Component";
</script>

<div class="title">
    <img src="/controller.svg" alt="ControllerImage">
    <h1>{title}</h1>
</div>


<style>
    .title
    {
        display:flex;
    }
    
    .title img
    {
        display:inline-block;
        filter:invert(88%) sepia(18%) saturate(886%) hue-rotate(199deg) brightness(100%) contrast(99%);

    }

    .title h1
    {
        margin-left:10px;
    }
</style>
