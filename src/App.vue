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
.main{
  background-color: #eccb8f88;
  position: absolute;
  z-index: -2;
  width: 100vw;
  min-height: 100vh;
}

</style>