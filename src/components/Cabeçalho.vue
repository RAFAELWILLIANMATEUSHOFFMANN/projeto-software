<template>
  <header class="cabeçalho">
    <h1>{{ titulo }}</h1>
  </header>
</template>

<script>
export default {
  data() {
    return {
      titulo: 'Este é o cabeçalho'
    }
  }
}
</script>

<style scoped>
.cabeçalho {
  background-color: #f8f9fa;
  padding: 20px;
  text-align: center;
}
</style>
