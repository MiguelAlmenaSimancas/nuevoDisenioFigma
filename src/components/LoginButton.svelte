<script>
    export let onClick;
</script>

<button on:click={onClick}>
    Iniciar sesión
</button>

<style>
    button {
        padding: 10px 20px;
        background-color: #6E675F;
        color: white;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        margin-top: 40px;
    }
</style>
