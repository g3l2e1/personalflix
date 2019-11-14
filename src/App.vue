<template>
  <div id="app">
    
    <nav class="flex items-center justify-between flex-wrap p-6">
      <div class="text-white mr-6">
        <img id="pflix-logo-nav" src="./assets/personalflix-logo-branco.svg">
      </div>
      <div class="">
        <div>
          <a href="#" class="inline-block text-sm px-4 py-2 leading-none border rounded text-white border-white hover:border-transparent hover:text-teal-500 hover:bg-white mt-4 lg:mt-0">
            Entrar
          </a>
        </div>
      </div>
    </nav>

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
  color: #2c3e50;
}
#pflix-logo-nav { height: 40px; }
</style>
