<script>

export default {
    name: 'Parte4'
}

</script>

<template>
    <div class="main">

        <div class="titulo">GALERIA DE FOTOS</div>
        <div class="fotos">
            <div class="linha">
                <img class="imagem" src="../assets/imagens/284180530_3108624156018439_7103310289403432985_n.jpg" alt="">
                <img class="imagem" src="../assets/imagens/284180530_3108624156018439_7103310289403432985_n.jpg" alt="">
            </div>
            <div class="linha">
                <img class="imagem" src="../assets/imagens/284180530_3108624156018439_7103310289403432985_n.jpg" alt="">
                <img class="imagem" src="../assets/imagens/284180530_3108624156018439_7103310289403432985_n.jpg" alt="">
            </div>
            <div class="linha">
                <img class="imagem" src="../assets/imagens/284180530_3108624156018439_7103310289403432985_n.jpg" alt="">
                <img class="imagem" src="../assets/imagens/284180530_3108624156018439_7103310289403432985_n.jpg" alt="">
            </div>
            <div class="linha">
                <img class="imagem" src="../assets/imagens/284180530_3108624156018439_7103310289403432985_n.jpg" alt="">
                <img class="imagem" src="../assets/imagens/284180530_3108624156018439_7103310289403432985_n.jpg" alt="">
            </div>
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
.fotos{
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
    gap: 5px;
}

.linha{
    display: flex;
    align-items: center;
    flex-direction: row;
    justify-content: center;
    gap: 5px;
}

.imagem{
    width: 45%;
    border-radius: 5%;
}

.titulo{
    font-size: 2rem;
    font-weight: 900;
    color: #fff;
    text-shadow: 0px 0px 20px #cc586b;
    padding: 5%;
}


</style>