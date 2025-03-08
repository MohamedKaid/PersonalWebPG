<script>
    let title = "Hi, my name is Mohamed Kaid";
    let image = "image/backgroundPic.png";
</script>

<style>
    @keyframes gradientAnimation {
        0% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
        100% { background-position: 0% 50%; }
    }

    .animated-bg {
        background: linear-gradient(270deg, #3b82f6, #9333ea, #f43f5e, #f59e0b);
        background-size: 400% 400%;
        animation: gradientAnimation 6s ease infinite;
    }
</style>

<main class="flex flex-col justify-center items-center h-screen bg-cover bg-center text-white" >
    <h1 class="text-4xl font-bold">{title}</h1>
</main>




