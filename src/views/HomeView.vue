<script>
import Parte1 from '/src/components/parte1.vue';
import Parte2 from '/src/components/parte2.vue';
import Parte3 from '/src/components/parte3.vue';
import Parte4 from '/src/components/parte4.vue';
import Parte5 from '/src/components/parte5.vue';
import Rodape from '/src/components/rodape.vue';
import Menu from '/src/components/header.vue';

export default {
  name: 'Home',

  components: {
    Parte1,
    Parte2,
    Parte3,
    Parte4,
    Parte5,
    Rodape,   
    Menu 
  }
}

</script>

<template>
  <div class="home">
    <div class="menu">
      
    <Menu/>
      </div>
    <div class="fundo1">

      <Parte1 />

    </div>
    <div class="fundo2">
      <Parte2 />
    </div>
    <div class="fundo3">
      <Parte3 />
    </div>
    <div class="fundo4">
      <Parte4 />
    </div>
    <div class="fundo5">
      <Parte5 />
    </div>
    <div class="rodape">
      <Rodape />
    </div>
  </div>
</template>

<style scoped>
.home {
}

.menu{
  position: fixed;
  width: 100%;
  z-index: 1;
}

.fundo1 {  
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  position: relative;
  height: 90vh;
}

.fundo2 {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  position: relative;
  min-height: 100vh;
}
.fundo3 {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  position: relative;
  min-height: 90vh;
}
.fundo4 {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  position: relative;
  min-height: 100vh;
}
.fundo5 {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  position: relative;
  min-height: 100vh;
}
.rodape {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  position: relative;
  min-height: 100vh;
}

.fundo1::after {
  content: '';
  display: flex;
  align-items: center;
  background-image: linear-gradient(  #4e2f4a,  #fbd8ff);
  background-size: cover;
  background-repeat: no-repeat;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  opacity: 0.9;
  /* ajuste a opacidade conforme necessário */
  z-index: -1;
  /* para colocar atrás do conteúdo */
}

.fundo2::after {
  content: '';
  background-image: linear-gradient( #fbd8ff, #4e2f4a);
  background-size: contain;
  background-repeat: no-repeat;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  opacity: 1;
  /* ajuste a opacidade conforme necessário */
  z-index: -1;
  /* para colocar atrás do conteúdo */
}

.fundo3::after {
  content: '';
  background-image: linear-gradient(  #4e2f4a,  #fbd8ff);
  background-size: cover;
  background-repeat: no-repeat;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  opacity: 1;
  /* ajuste a opacidade conforme necessário */
  z-index: -1;
  /* para colocar atrás do conteúdo */
}
.fundo4::after {
  content: '';
  background-image: linear-gradient( #fbd8ff, #4e2f4a);
  background-size: contain;
  background-repeat: no-repeat;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  opacity: 1;
  /* ajuste a opacidade conforme necessário */
  z-index: -1;
  /* para colocar atrás do conteúdo */
}
.fundo5::after {
  content: '';
  background-image: linear-gradient(#4e2f4a,  #fbd8ff);
  background-size: contain;
  background-repeat: no-repeat;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  opacity: 1;
  /* ajuste a opacidade conforme necessário */
  z-index: -1;
  /* para colocar atrás do conteúdo */
}
.rodape::after {
  content: '';
  background-image: linear-gradient( #fbd8ff, #4e2f4a);
  background-size: contain;
  background-repeat: no-repeat;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  opacity: 1;
  /* ajuste a opacidade conforme necessário */
  z-index: -1;
  /* para colocar atrás do conteúdo */
}

</style>
