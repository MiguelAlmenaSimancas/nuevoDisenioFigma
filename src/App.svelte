<script>
    import ImageGrid from './components/ImageGrid.svelte';
    import LoginForm from './components/LoginForm.svelte';

    const images = [
        '/images/image1.jpeg',
        '/images/image2.jpeg',
        '/images/image3.jpeg',
        '/images/image4.jpeg'
    ];
</script>

<div class="container">
    <div class="images-section">
        <ImageGrid {images} />
    </div>
    <div class="form-section">
        <LoginForm />
    </div>
</div>

<style>
    .container {
        display: flex;
        height: 100vh; 
        width: 100%;
    }
    .images-section {
        width: 50%;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .form-section {
        width: 50%;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: #fff;
    }
</style>
