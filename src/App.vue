<script setup lang="ts">
import Main from './components/Main.vue';

</script>

<script lang="ts">
  export default {
    name: 'App',
    components: {
      Main,
    },
  }
</script>
<template>
  <body>
  </body>
  <Main msg="gydo.js" />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #131313;
  margin-top: 60px;
}

</style>
