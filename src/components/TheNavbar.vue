<template>
    <nav>
        <div class="nav-logo">
            <a href="#"><img :src="jomfdev" alt="JoMF.Dev"></a>
        </div>

        <ul class="nav-links">
            <li class="link"><a href="##">Início</a></li>
            <li class="link"><a href="##">Sobre mim</a></li>
            <li class="link"><a href="##">Habilidades</a></li>
            <li class="link"><a href="##">Projetos</a></li>
            <li class="link"><a href="##">Tecnologias</a></li>
        </ul>
        <button class="btn">Entre em contato!</button>
    </nav>
</template>

<script>
    export default { 
    data() {
      return {
        jomfdev: "https://i.imgur.com/cXElGiS.png"
      }
    }
  }
</script>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

    * {
        margin: 0;
        padding: 0;
        outline: none;
        border: none;
        box-sizing: border-box;
    }

    a { 
        text-decoration: none;
    }

    img {
        width: 100%;
        display: flex;
    }

    body {
        background-color: #000;
        font-family: 'Poppins', sans-serif;
    }

    nav {
        max-width: 1200px;
        margin: auto;
        padding: 1rem;
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 2rem;
    }

    .nav-logo {
        max-width: 310px;
    }

    .nav-links {
        list-style: none;
        display: flex;
        align-items: center;
        gap: 3rem;
    }

    .link a {
        position: relative;
        color: #6600ff;
        padding-bottom: 0.75rem;
    }

    .link a::after {
        content: "";
        position: absolute;
        height: 2px;
        width: 0;
        bottom: 0;
        left: 0;
        transition: all 0.3s ease;
        background-color: #6600ff;
    }

    .link a:hover::after {
        width: 80%;
    }

    .btn {
        padding: 1rem 2rem;
        font-size: 1rem;
        color: white;
        background-color: #6600ff;
        border-radius: 5px;
        cursor: pointer;
        transition: all 0.3s ease;
    }

    .btn:hover {
        background-color: #5200cc;
    }
</style>