<template>
  <div id="app">
    <input v-model="ime" placeholder="Ime"><br>
    <input v-model="prezime" placeholder="Prezime">
    <p>Ime i prezime: {{ ime }} {{ prezime }}</p>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

export default {
  name: 'Moja aplikacija',
  components: {
    
  },
  data(){
    return {
      ime:'',
      prezime:'',
    };
  },

}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
