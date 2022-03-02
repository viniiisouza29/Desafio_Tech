<template>
  <div>
    <modelo />
    <trilho />
    <camadas />
  </div>
</template>

<script>
  import Modelo from './components/Modelo.vue';
  import Trilho from './components/Trilho.vue';
  import Camadas from './components/Camadas.vue';

  export default {
    name: 'App',

    components: {
      Modelo,
      Trilho,
      Camadas
  }
}
</script>