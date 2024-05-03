<script>

export default{
    name: 'Parte1'
}

</script>

<template>

    <div class="main">
        
        <img class="imagem" src="../assets/imagens/284180530_3108624156018439_7103310289403432985_n.jpg" alt="">

        <div class="subtitulo">
            UNHAS PERFEITAS EM MINUTOS!
        </div>

        <div class="texto">
            Realce sua beleza com nossos serviços exclusivos de nail design.
            Agende agora e surpreenda-se com resultados incríveis!
        </div>

        <div class="btn">
            WhattsApp
        </div>

    </div>

</template>

<style scoped>

.main{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.imagem{
    width: 50%;
    border-radius: 10%;
}

.subtitulo{
    color: #fff;
    font-size: 2rem;
    text-align: center;
    text-justify: distribute-all-lines;
    font-weight: 500;
    padding: 5% 0%;
    text-shadow: 0px 0px 10px #000;
}

.texto{
    color: #000;
    font-size: 0.9rem;
    text-align: center;
    font-weight: bold;
    padding: 5%;
    text-align: center;
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