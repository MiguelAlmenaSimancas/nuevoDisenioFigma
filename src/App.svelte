<script>
    import LoginForm from './components/LoginForm.svelte';
</script>
<body>

<div class="container">
    <h1>Limited Football</h1>
    <div class="form-section">
        <div class="imagen-logo">
            <img src="public/images/luisaragones.png" alt="logo" class="logo-balon" />
        </div>
        <LoginForm />
        <div class="imagen-logo">
            <img src="public/images/luisaragones.png" alt="logo" class="logo-balon" />
        </div>
    </div>
</div>
</body>

<style>

    h1{
        color: white;
        margin-top: 50px;
        margin-bottom: 70px;
    }
    .container {
        display: flex;
        align-items: center;
        flex-direction: column;
        height: 100vh; 
        width: 100%;
        background-color: #5964a0;
    }

    .form-section {
        width: 50%;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
</style>
