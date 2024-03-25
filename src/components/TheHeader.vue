<template>
    <header class="container">
        <div class="content">
            <span class="blur"></span>
            <span class="blur"></span>
            <h1>Olá, eu sou o <span>Jóshua Martins!</span></h1>
            <p>Nascido na cidade de Manaus, AM, sou apaixonado por tecnologia desde os meus 6 anos de idade. Ainda na
                adolescência, tive meu primeiro contato com programação e aos 17 anos, ao completar o ensino médio,
                decidi embarcar na carreira para me tornar, um dia, um desenvolvedor full stack.
                <span>Hoje, com 18 anos, estou cursando Análise e Desenvolvimento de Sistemas (3/5) na UniFAVIP.</span>
            </p>
            <button class="btn">Entre em contato!</button>
        </div>
        <div class="image">
            <img src="https://i.imgur.com/0heueVu.jpg">
        </div>
    </header>
</template>

<script>
</script>

<style>
    .container {
        max-width: 1200px;
        margin: auto;
        padding: 5rem 2rem;
    }

    .blur {
        position: absolute;
        box-shadow: 0 0 1000px 50px #6200ff;
        z-index: -100;
        left: 10%;
        top: 20%;
    }

    header {
        position: relative;
        padding-top: 2rem;
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        align-items: center;
        gap: 2rem;
    }

    header .content h4 {
        color: #ccc;
        font-weight: 600;
        padding-bottom: 1rem;
        font-size: 1rem;
    }

    header .content h1 {
        color: #ccc;
        margin-bottom: 12px;
        line-height: 4rem;
        font-weight: 700;
        font-size: 4rem;
    }

    header .content h1 span {
        color: #5200cc;
    }

    header .content p {
        margin-bottom: 2rem;
        color: #ccc;
    }

    header .image {
        position: relative;
    }

    header .image img {
        max-width: 600px;
        margin: auto;
        border-radius: 50px;
        max-height: 1100px;
    }
</style>