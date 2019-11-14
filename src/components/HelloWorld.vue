<template>
  <div class="max-w-sm rounded overflow-hidden" id="initial-card">
    <div class="px-6 py-4">
      <h1>Personalflix</h1>
      <p class="text-gray-300 text-base">
        A Netflix-style cloud-hosted personal movie manager. Um gerenciador de filmes pessoais.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#initial-card { position: fixed; bottom: 1em; left: 0.5rem; }
#initial-card h1 { font-size: 2rem;  color: dodgerblue; font-weight: bolder; }
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
