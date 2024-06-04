<template>
  <div>
    <HelloWorld />
    <ListaClientes />
    <Cabecalho />
    <BarraLateral />
    <!-- Outros componentes aqui -->
    <Formulario />
    <Rodape />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorldNew.vue'
import ListaClientes from './components/ListaClientes.vue'
import Cabecalho from './components/MeuCabeçalho.vue'
import BarraLateral from './components/BarraLateral.vue'
import Formulario from './components/Formulario.vue'
import Rodape from './components/Rodape.vue'

export default {
  name: 'App',
  components: {
  HelloWorld,
  ListaClientes,
  Cabecalho,
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
