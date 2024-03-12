<template>
    <header class="container">
        
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

    section .header {
        margin-bottom: 1rem;
        color: #fff;
        text-align: center;
        font-size: 3rem;
        font-weight: 600;
    }

    .habilities {
        margin-top: 4rem;
        display: grid;
        grid-template-columns: repeat(4, 1fr);
        gap: 3rem;
    }

    .habilities .card {
        background-color: #27272a;
        border-radius: 15px;
        padding: 1rem;
        border: 2px solid transparent;
        transition: all 0.3s ease;
    }

    .habilities .card:hover {
        background-color: #323232;
        border-color: #fff;
    }

    .habilities .card span {
        background-color: #6200ff;
        border-radius: 5px;
        margin-bottom: 1rem;
        font-size: 1.75rem;
        display: inline-block;
        color: #fff;
        padding: 2px 9px;
    }

    .habilities .card h4 {
        margin-bottom: 0.5rem;
        color: #fff;
        font-weight: 600;
        font-size: 1.5rem;
    }

    .habilities .card p {
        color: #ccc;
        margin-bottom: 0.5rem;
    }

    .habilities .card a {
        color: #fff;
        transition: all 0.3s ease;
    }

    .habilities .card a:hover {
        color: #5200cc;
    }
</style>