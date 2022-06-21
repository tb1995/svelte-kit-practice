<script>
    let title='sample ';
</script>
<div class="sample">
    <img src="/controller.svg" alt="controller" />
    <h1>{title}</h1>

</div>

<style>
    .sample
    {
        display: flex;
    }

    .sample img
    {
        display: inline-block;
        filter:invert(88%) sepia(18%) saturate(886%) hue-rotate(199deg) brightness(100%)
        contrast(90%);
    }

    .sample h1{
        margin-left: 10px;
    }
</style>