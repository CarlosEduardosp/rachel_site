<script>

export default {
    name: 'Menu'
}
</script>

<template>
    <div class="main">
        <div class="logo">
            <img class="imagem" src="../assets/imagens/284180530_3108624156018439_7103310289403432985_n.jpg" alt="">
        </div>
        <div class="titulo">
            RACHEL COSTA
        </div>
        <nav class="nav">
            <router-link class="item_menu" to="/">Home</router-link> 
            <p class="item_menu">|</p>
            <router-link class="item_menu" to="/sobre">Sobre</router-link>
            <a href="https://www.instagram.com/rachelcosta_0/"><img class="icone" src="../assets/imagens/instagram.png" alt="" ></a>
            <a href="https://www.facebook.com/rachel.nogueiracosta/"><img class="icone" src="../assets/imagens/facebook.png" alt=""></a>
            <a href="/"><img class="icone" src="../assets/imagens/whatsapp.png" alt=""></a>
        </nav>
        
        <router-view />
    </div>
</template>

<style scoped>
.main {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    background-color: #fff;
    height: 4rem;
    box-shadow: 0px 0px 10px 1px #cc586b;
}

.nav{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    margin-left: 0.5rem;
}

.titulo {
    font-size: 1rem;
    font-weight: bold;
    color: #a32893;
    width: auto;
}

.item_menu {
    list-style-type: none;
    text-decoration: none;
    font-size: 1rem;
    color: #a32893;
    margin-right: 4px;
}

.imagem {
    width: 3rem;
}
.icone{
    width: 1.5rem;
    margin: 0px 0.2rem;
}


</style>