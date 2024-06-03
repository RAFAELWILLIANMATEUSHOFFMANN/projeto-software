<template>
  <div>
     <label>Lista de Clientes</label>
    <select name="ListaClientes" id="ListaClientes">
      <option value="">Selecione </option>
      <option value="cliente1">Petrobras</option>
      <option value="cliente2">Vale do Rio DOCE</option>
      <option value="cliente3">Transpetro</option>
    </select>
    
  </div>
</template>

<script>
export default {
  name: 'ListaClientes',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

label {
  color: #5842b9;
  font-size: 20pix;
}
select {
  color: #e71b1b;
  background-color: black;
  font-size: 19pix;
}
</style>
