<script>
import Parte1 from '/src/components/parte1.vue';
import Parte2 from '/src/components/parte2.vue';
import Parte3 from '/src/components/parte3.vue';

export default {
  name: 'Home',

  components: {
    Parte1,
    Parte2,
    Parte3
  }
}

</script>

<template>
  <div class="home">
    <div class="fundo1">

      <Parte1 />

    </div>
    <div class="fundo2">
      <Parte2 />
    </div>
    <div class="fundo3">
      <Parte3 />
    </div>
  </div>
</template>

<style scoped>
.home {
}

.fundo1 {  
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  position: relative;
  min-height: 75vh;
}

.fundo2 {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  position: relative;
  min-height: 88vh;
}

.fundo1::after {
  content: '';
  background-image: url(../assets/imagens/folhas-douradas-de-fundo-roxo-claro-com-espaco-para-copia_1000823-67083.jpg);
  background-size: contain;
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
