<script>
    let email = '';
    let password = '';
</script>

<div class="login-form">
    <h1>Iniciar Sesión</h1>
    <h3>Bienvenido de nuevo</h3>
    <input type="email" bind:value={email} placeholder="Correo electrónico" />
    <input type="password" bind:value={password} placeholder="Contraseña" />
    <button>Iniciar Sesión</button>
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
        height: 100%;
    }
    input {
        width: 80%;
        padding: 10px;
        margin: 5px 0;
        border: 1px solid #ccc;
        border-radius: 5px;
    }
    button {
        padding: 10px 20px;
        background-color: #007BFF;
        color: white;
        border: none;
        border-radius: 5px;
        cursor: pointer;
    }
    p {
        font-size: 0.9rem;
    }
    a {
        color: #007BFF;
        text-decoration: none;
    }
</style>
