<script>
    export let images = [];
</script>

<div class="image-grid">
    {#each images as img}
        <img src={img} alt="Imagen de ejemplo" />
    {/each}
</div>

<style>
    .image-grid {
        display: grid;
        grid-template-columns: repeat(2, 250px);
        width: 500px;
        height: 700px;
        margin: 0;
        padding: 0;
    }
    img {
        width: 250px;
        height: 350px;
        object-fit: cover;
        margin: 0;
    }
</style>
