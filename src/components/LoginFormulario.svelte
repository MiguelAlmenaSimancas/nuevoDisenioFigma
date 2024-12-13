<script>
    let email = '';
    let password = '';
    import Boton from "./Boton.svelte";
</script>

<div class="login-formulario">
    <h1>LOG IN👤</h1>
    <input type="user" bind:value={email} placeholder="User Name" />
    <input type="password" bind:value={password} placeholder="Password" />
    <Boton />
    <p class="texto-crearcuenta">¿No tienes cuenta?<a href="#">Crear Cuenta</a></p>
</div>

<style>
    .login-formulario {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 10px;
        padding: 20px;
        height: 450px;
        border-radius: 18px;
        background-color: #ffffff;
    }
    input {
        width: 300px;
        padding: 10px;
        margin: 5px 0;
        border: 10px solid #ccc;
        border-radius: 5px;
    }

    .texto-crearcuenta {
        font-size: 0.9rem;
    }
    a {
        color: rgb(0, 132, 255);
        text-decoration: solid;
    }

</style>
