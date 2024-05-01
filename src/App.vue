<template>
  <div class="main">
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/sobre">Sobre</router-link>
  </nav>
  <router-view/>
  </div>
</template>

<style scoped>

@media (max-width: 720px) {
  .main{
    height: auto;
    background: linear-gradient(#f3f3f3, #FF00FF);
    background-position: center, center;
    background-size: cover;
    background-position-y: 0px;
    background-repeat: no-repeat;
    min-height: 100vh;
    max-width: 100vw;
  }
}


</style>