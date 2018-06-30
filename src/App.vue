<template>
  <div id="app">
    <img src="./assets/logoSC.png">
    <h1> Ceci est un test </h1>

    <!-- Début des lignes ajoutées par Francois Provencher -->
    <!-- fin des lignes ajoutées par Francois Provencher -->








    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
