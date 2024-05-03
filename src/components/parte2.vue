<script>

export default {
    name: 'Parte2'
}

</script>

<template>
    <div class="main">

        <p class="texto">
            Explore um mundo de criatividade e elegância onde cada unha é uma tela em branco esperando para ser
            transformada em uma obra de arte. Descubra uma variedade de estilos, desde os mais clássicos aos mais
            ousados, projetados para elevar a sua beleza e expressão pessoal.

            Navegue pelas nossas galerias para inspiração ilimitada e mergulhe em um mundo de cores vibrantes, técnicas
            inovadoras e designs impressionantes. Deixe-nos cuidar das suas mãos e transformar sua imaginação em
            realidade.

            Seja Muito bem-vindo.
        </p>

        <img class="imagem" src="../assets/imagens/manutencaoalongamento-de-unhas-compressed-1.jpg" alt="">

    </div>
</template>

<style scoped>

.main{
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
}

.texto{
    font-size: 0.8rem;
    padding: 10%;
    text-align: justify;
    justify-content: center;
    letter-spacing: 1px;
    line-height: 1.5rem
}

.imagem{
    width: 70%;
    border-radius: 45%;
    box-shadow: 0px 0px 20px 5px #cc586b;
}

</style>