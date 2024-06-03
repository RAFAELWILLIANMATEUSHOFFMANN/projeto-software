<template>
  <footer class="rodapé">
    <p>rodapé</p>
  </footer>
</template>

<script>
import HelloWorld from './components/HelloWorldNew.vue'
import ListaClientes from './components/ListaClientes.vue'
import Cabeçalho from './components/Cabeçalho.vue'
import BarraLateral from './components/BarraLateral.vue'
import Formulario from './components/Formulario.vue'
import Rodape from './components/Rodape.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    ListaClientes,
    Cabeçalho,
    BarraLateral,
    Formulario,
    Rodape
  }
}
</script>

<style>
.rodapé {
  background-color: #f8f9fa;
  padding: 20px;
  text-align: center;
}
</style>
