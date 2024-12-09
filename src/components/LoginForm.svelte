<script>
    let email = '';
    let password = '';
    import LoginButton from "./LoginButton.svelte";
</script>

<div class="login-form">
    <h1>Unique Football</h1>
    <h2>Iniciar Sesión</h2>
    <input type="email" bind:value={email} placeholder="Correo electrónico" />
    <input type="password" bind:value={password} placeholder="Contraseña" />
    <LoginButton />
    <p>¿No tienes cuenta? <a href="#">Créate una</a></p>
</div>

<style>
    .login-form {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 10px;
        padding: 20px;
        height: 450px;
        border-radius: 18px;
        background-color: #EDEBD7;
    }
    input {
        width: 300px;
        padding: 10px;
        margin: 5px 0;
        border: 1px solid #ccc;
        border-radius: 5px;
    }
    button {
        padding: 10px 20px;
        background-color: #6E675F;
        color: white;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        margin-top: 40px;
    }
    p {
        font-size: 0.9rem;
    }
    a {
        color: black;
        text-decoration: solid;
    }

</style>
