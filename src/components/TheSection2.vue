<template>
    <section class="container">
        <h2 class="header">
            Meus Projetos
        </h2>
        <p class="sub-header">Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore, mollitia.</p>
        <div class="projects">
            <div class="card">
                <div class="content">
                    <h4>Projeto #1</h4>
                    <p><i class="ri-bug-fill"></i>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, cum.
                    </p>
                    <p><i class="ri-bug-fill"></i>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, cum.
                    </p>
                    <p><i class="ri-bug-fill"></i>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, cum.
                    </p>
                </div>
                <button class="btn">Visualizar Projeto</button>
            </div>
            <div class="card">
                <div class="content">
                    <h4>Projeto #2</h4>
                    <p><i class="ri-bug-fill"></i>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, cum.
                    </p>
                    <p><i class="ri-bug-fill"></i>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, cum.
                    </p>
                    <p><i class="ri-bug-fill"></i>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, cum.
                    </p>
                </div>
                <button class="btn">Visualizar Projeto</button>
            </div>
            <div class="card">
                <div class="content">
                    <h4>Projeto #3</h4>
                    <p><i class="ri-bug-fill"></i>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, cum.
                    </p>
                    <p><i class="ri-bug-fill"></i>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, cum.
                    </p>
                    <p><i class="ri-bug-fill"></i>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, cum.
                    </p>
                </div>
                <button class="btn">Visualizar Projeto</button>
            </div>
        </div>
    </section>

</template>

<script>

</script>

<style>
.sub-header {
    max-width: 600px;
    text-align: center;
    color: #ccc;
    margin: auto;
}

.projects {
    display: grid;
    grid-template-columns: repeat(3, 2fr);
    margin-top: 4rem;
    gap: 2rem;
}

.projects .card {
    background-color: #27272a;
    border-radius: 15px;
    padding: 3rem 2rem;
    border: 2px solid transparent;
    transition: all 0.3s ease;
    display: flex;
    flex-direction: column;
}

.projects .card:hover {
    background-color: #323232;
    border-color: #fff;
}

.projects .card .content {
    flex: 1;
    margin-bottom: 2rem;
}

.projects .card h4 {
    font-weight: 600;
    color: #fff;
    font-size: 2rem;

}

.projects .card p {
    margin-top: 0.75rem;
    color: #ccc;
}

@media (width >=915px) {
    .btn-menu {
        visibility: hidden;
        display: none;
    }
}

@media (width < 900px) {

    .nav-links,
    .btn,
    .nav-logo {
        visibility: hidden;
    }


    header {
        grid-template-columns: repeat(1, 1fr);
    }

    header .image {
        grid-area: 1/1/2/2;
    }

    .habilities {
        grid-template-columns: repeat(2, 1fr);
    }

    .projects {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (width < 600px) {
    header .image::before {
        display: none;
    }

    header {
        grid-template-columns: repeat(1, 1fr);
    }

    header .image {
        grid-area: 1/1/2/2;
    }

    .habilities {
        grid-template-columns: repeat(1, 1fr);
    }

    .projects {
        grid-template-columns: repeat(1, 1fr);
    }
}
</style>