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
        grid-template-columns: repeat(2, 1fr);
        gap: 10px;
        width: 100%;
        height: 100%;
    }
    img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        border-radius: 8px;
    }
</style>
