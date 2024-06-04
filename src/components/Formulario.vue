<template>
  <div class="formulario">
    <button @click="handleClick">Clique em mim</button>
    <form>
      <label for="nome">Nome:</label><br>
      <input type="text" id="nome" v-model="nome"><br>
      <input type="submit" value="Enviar" @click.prevent="submitForm">
    </form>
  </div>
</template>

<script>
export default {
  data() {
    return {
      nome: ''
    }
  },
  methods: {
    handleClick() {
      alert('Você clicou no botão!');
    },
    submitForm() {
      alert(`Nome enviado: ${this.nome}`);
      this.nome = '';
    }
  }
}
</script>

<style scoped>
.formulario {
  background-color: #fff;
  padding: 20px;
}
</style>

