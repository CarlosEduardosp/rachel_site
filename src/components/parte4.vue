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
    color: #fff;
    font-size: 2rem;
    font-weight: 1000;
    text-align: center;
    padding: 4%;
    text-shadow: #4e2f4a 0px 5px 15px ;

}


</style>