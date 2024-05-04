<script>

export default {
    name: 'Rodape'
}

</script>

<template>
    <div class="main">

        
        <img class="imagem" src="../assets/imagens/284180530_3108624156018439_7103310289403432985_n.jpg" alt="">
        
        <p class="texto">
            "É uma honra atender clientes tão incríveis como você. Agradecemos por sua confiança e preferência."
        </p>

        <p class="titulo">ME ACOMPANHE NAS REDES</p>

        <div class="icones">
        <a href="https://www.instagram.com/rachelcosta_0/"><img class="icone" src="../assets/imagens/instagram.png" alt="" ></a>
            <a href="https://www.facebook.com/rachel.nogueiracosta/"><img class="icone" src="../assets/imagens/facebook.png" alt=""></a>
            <a href="/"><img class="icone" src="../assets/imagens/whatsapp.png" alt=""></a>
            </div>
    </div>
</template>

<style scoped>

.main{
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.texto{
    font-size: 1.3rem;
    padding: 10%;
    text-align: center;
    justify-content: center;
    letter-spacing: 1.5px;
    line-height: 1.5rem;
    color: #f3f3f3;
}

.imagem{
    width: 70%;
    border-radius: 20%;
    box-shadow: 0px 0px 20px 2px #000000;
    margin-top: 15%;
}

.icones{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    background-color: #f3f3f3;
    border-radius: 10px;
    width: auto;
    height: auto;
    padding: 3%;
}

.titulo{
    color: #f3f3f3;
    font-size: 0.9rem;
    margin-bottom: 5%;
    margin-top: 10%;
}

.icone{
    width: 3rem;
    margin: 0px 1rem;
}
</style>