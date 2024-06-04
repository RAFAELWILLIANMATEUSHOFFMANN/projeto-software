<template>
  <aside class="barra-lateral">
    <h2>{{ titulo }}</h2>
  </aside>
</template>

<script>
export default {
  data() {
    return {
      titulo: 'Esta é a barra lateral'
    }
  }
}
</script>

<style scoped>
.barra-lateral {
  background-color: #e9ecef;
  padding: 20px;
}
</style>
