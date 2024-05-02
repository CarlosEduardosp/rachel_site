<script>

export default{
    name: 'Parte1'
}

</script>

<template>

    <div class="main">
        
        <div class="titulo">
            NAIL DESIGN
        </div>

        <div class="logo">
            RACHEL COSTA
        </div>

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

.titulo{
    color: #000;
    font-size: 1.2rem;
    font-weight: bold;
}

.logo{
    color: #fff;
    background-color: #000000cb;
    border-radius: 5%;
    box-shadow: 0px 0px 10px 2px #eccb8f;
    padding: 3%;
    margin: 5%;
    font-size: 1.5rem;
    font-weight: bolder;
}

.subtitulo{
    color: #fff;
    font-size: 2rem;
    text-align: center;
    text-justify: distribute-all-lines;
    font-weight: 500;
    padding: 5% 0%;
    text-shadow: 0px 0px 20px #000;
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
    background-color: #eccb8f;
    font-size: 1.5rem;
    font-weight: bolder;
    padding: 3%;
    border: 1px solid #fff;
    border-radius: 20px;
    color: #000;
}
</style>