<script>

export default{
    name: 'Menu'
}
</script>

<template>
    <div class="main">
        <div class="titulo">
            RACHEL COSTA
        </div>
        <nav>
            <router-link class="item_menu" to="/">Home</router-link> |
            <router-link class="item_menu" to="/sobre">Sobre</router-link>
        </nav>
        <div class="logo">
            <img class="imagem" src="../assets/imagens/284180530_3108624156018439_7103310289403432985_n.jpg" alt="">
        </div>
        <router-view/>
    </div>
</template>

<style scoped>

.main{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content:space-around;
    background-color: #fff;
    height: 3rem;
    box-shadow: 0px 0px 10px 1px #cc586b;
}

.titulo{
    font-size: 1.1rem;
    font-weight: bold;
    color: #a32893;
}

.item_menu{
    list-style-type: none;
    text-decoration: none;
    font-size: 1rem;
    color: #a32893;
}

.imagem{
    width: 3rem;
}

</style>