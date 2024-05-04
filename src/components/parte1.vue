<script>

export default{
    name: 'Parte1'
}

</script>

<template>

    <div class="main">
        
        <img class="imagem" src="../assets/imagens/kisspng-businessperson-stock-photography-woman-happy-women-5abea8aa2605c5.9011973015224444581558.png" alt="">

        <div class="subtitulo">
            UNHAS PERFEITAS EM MINUTOS!
        </div>

        <div class="texto">
            Realce sua beleza com nossos serviços exclusivos de nail design.
            Agende agora e surpreenda-se com resultados incríveis!
        </div>

        <div class="btn">
            AGENDAR HORÁRIO
        </div>

    </div>

</template>

<style scoped>

.main{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100%;
}

.imagem{
    width: 80%;
    border-radius: 10%;
    margin-bottom: 5%;
    margin-top: 15%;
}

.subtitulo{
    color: #fff;
    font-size: 2rem;
    font-weight: 1000;
    text-align: center;
    padding: 4%;
    text-shadow: #4e2f4a 0px 5px 30px ;
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
    font-size: 1rem;
    font-weight: bolder;
    padding: 3%;
    border: 2px solid #cc586b;
    border-radius: 20px;
    color: #cc586b;
}
</style>