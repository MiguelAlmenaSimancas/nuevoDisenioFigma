<script>
    export let onClick;
</script>

<button on:click={onClick}>
    -- Log In --
</button>

<style>
    button {
        padding: 10px 20px;
        background-color: #5964a0;
        color: white;
        font-family: 'Times New Roman', Times, serif;
        font-size: larger;
        padding: 15px;
        padding-left: 20px;
        padding-right: 20px;
        border: none;
        border-radius: 15px;
        cursor: pointer;
        margin-top: 40px;
    }
</style>
