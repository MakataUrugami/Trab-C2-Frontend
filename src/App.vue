<template>
  <div id="app">
    <nav class="navbar navbar-expand navbar-dark bg-dark">
      <a href="#" class="navbar-brand">DevWebII</a>
      <div class="navbar-nav mr-auto">
        <li class="nav-item">
          <a href="/pacientes" class="nav-link">Pacientes</a>
        </li>
        <li class="nav-item">
          <a href="/adicionar" class="nav-link"> Adicionar</a>
        </li>
      </div>
    </nav>
    <div class="container mt-3">
      <router-view />

    </div>
  </div>
</template>

<script>

//import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    //HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
