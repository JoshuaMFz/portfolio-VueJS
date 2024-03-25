<template>
    <section class="container">
        <h2 class="header">Minhas Habilidades</h2>
        <div class="habilities">
            <div class="card">
                <span><i class="ri-user-2-fill"></i></span>
                <h4>Excelente Comunicação</h4>
                <p>Com minha experiência profissional, desenvolvi sólidas habilidades de comunicação tanto em público
                    como em equipe.</p>
            </div>
            <div class="card">
                <span><i class="ri-team-fill"></i></span>
                <h4>Trabalho em Equipe</h4>
                <p>Contribuo ativamente, comunico-me claramente e resolvo conflitos de maneira construtiva. Estou sempre
                    encorajando e ensinando.</p>
            </div>
            <div class="card">
                <span><i class="ri-user-search-fill"></i></span>
                <h4>Constante Evolução</h4>
                <p>Ciente do avanço tecnológico atual, estou certo de que é necessário o avanço contínuo em aprender
                    novas tecnologias e se atualizar todos os dias. </p>
            </div>
        </div>
    </section>
</template>



<script>

</script>

<style>
section .header {
    margin-bottom: 1rem;
    color: #fff;
    text-align: center;
    font-size: 3rem;
    font-weight: 600;
}

.habilities {
    display: grid;
    grid-template-columns: repeat(3, 2fr);
    margin-top: 4rem;
    gap: 2rem;
}

.habilities .card {
    background-color: #27272a;
    border-radius: 15px;
    padding: 3rem 2rem;
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