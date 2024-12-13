<script>
    import LoginForm from './components/LoginFormulario.svelte';
</script>
<body>

<div class="contenedor-principal">
    <h1>-- Limited Football --</h1>
    <div class="formulario-contenedor">
        <div class="imagen-logo">
            <img src="images/balonLogo.png" alt="logo" class="logo-balon" />
        </div>
        <LoginForm />
        <div class="imagen-logo">
            <img src="images/balonLogo.png" alt="logo" class="logo-balon" />
        </div>
    </div>
</div>
</body>

<style>

    h1{
        color: white;
        margin-top: 50px;
        margin-bottom: 65px;
    }
    .contenedor-principal {
        display: flex;
        align-items: center;
        flex-direction: column;
        height: 100vh; 
        width: 100%;
        background-color: #5964a0;
    }

    .formulario-contenedor {
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 100px;

    }
    .logo-balon{
        width: 200px;
        height: 200px;
    }
</style>
