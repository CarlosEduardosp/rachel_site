<script>

export default {
    name: 'Parte5'
}

</script>

<template>
    <div class="main">

        <p class="titulo">
            OPNIÕES QUE NOS INSPIRAM!!
        </p>
        <div class="card">
            <img class="imagem" src="../assets/imagens/manutencaoalongamento-de-unhas-compressed-1.jpg" alt="">
            <p class="texto">
                Opnião de clientes satisfeitos com os resultados ou atendimentos, ou qualquer outra coisa.     
            </p>
            <p class="nome">Nome do Cliente</p>
        </div>
        <div class="card">
            <img class="imagem" src="../assets/imagens/manutencaoalongamento-de-unhas-compressed-1.jpg" alt="">
            <p class="texto">
                Opnião de clientes satisfeitos com os resultados ou atendimentos, ou qualquer outra coisa.     
            </p>
            <p class="nome">Nome do Cliente</p>
        </div>
        <div class="card">
            <img class="imagem" src="../assets/imagens/manutencaoalongamento-de-unhas-compressed-1.jpg" alt="">
            <p class="texto">
                Opnião de clientes satisfeitos com os resultados ou atendimentos, ou qualquer outra coisa.     
            </p>
            <p class="nome">Nome do Cliente</p>
        </div>
        <div class="btn">
            WhattsApp
        </div>
        

    </div>
</template>

<style scoped>

.main{
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
}

.titulo{
    color: #f3f3f3;
    font-size: 2rem;
    font-weight: 1000;
    text-align: center;
    padding: 2%;
}

.card{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 80%;
    background-color: rgb(228, 231, 233);
    padding: 4%;
    border-radius: 5%;
    margin: 2%;
}

.imagem{
    width: 30%;
    border-radius: 15%;
}

.texto{
    text-align: center;
    padding: 3%;
    font-size: 1rem;
}

.nome{
    font-size: 1.2rem;
    font-weight: 500;
}

.btn{
    background-color: #fff;
    font-size: 1.5rem;
    font-weight: bolder;
    padding: 3%;
    border: 2px solid #cc586b;
    border-radius: 20px;
    color: #cc586b;
}

</style>