<script>

export default{
    name: 'Menu'
}
</script>

<template>
    <div class="main">
        <nav>
            <router-link to="/">Home</router-link> |
            <router-link to="/sobre">Sobre</router-link>
        </nav>
        <router-view/>
    </div>
</template>

<style scoped></style>