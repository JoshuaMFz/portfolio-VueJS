<template>
    <nav class="links">
        <div class="nav-logo">
            <a href="#"><img :src="jomfDev" alt="JoMF.Dev"></a>
        </div>
        <button class="btn-menu"><i class="ri-menu-line"><span>Menu</span></i></button>
        <ul class="nav-links">
            <li class="link" v-for="item in links" :key="item.url">
                <a :href="item.url">{{ item.text }}</a>
            </li>
        </ul>
        <button class="btn">Entre em contato!</button>
    </nav>
</template>

<script>
export default {
    data() {
        return {
            jomfDev: "https://i.imgur.com/cXElGiS.png",
            links: [{
                text: 'Inicio',
                url: '/inicio',
            },
            {
                text: 'Sobre mim',
                url: '/sobremim'
            },
            {
                text: 'Habilidades',
                url: '/habilidades',
            },
            {
                text: 'Tecnologias',
                url: '/tecnologias'
            },
            {
                text: 'Projetos',
                url: '/projetos'
            },


            ]
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

.btn-menu {
    cursor: pointer;
    background-color: transparent;
    color: #6600ff;
    font-family: 'Poppins', sans-serif;
    font-size: 1rem;
}
</style>