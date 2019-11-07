<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld valor=2452 msg="Hi There" textp1="Olá, esse é um paragrafo criado" textprincipal="Esse é o
     main content da página, aqui contém os links mais importantes, 
     além do conteudo principal do seu site, está dentro de um tag <main></main> para indicar que
     é o seu conteúdo principal"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',        
  components: { 
    HelloWorld
  }
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