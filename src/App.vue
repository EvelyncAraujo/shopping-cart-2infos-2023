<script setup>
import ListagemLivros from '@/components/ListagemLivros.vue';
import MeuCarrinho from '@/components/MeuCarrinho.vue';
</script>

<template>
  <h1>Minha livraria</h1>
  <div class="container-geral">
    <listagem-livros />
    <meu-carrinho />
  </div>
</template>

<style scoped>
.container-geral {
  /* display: flex;
  justify-content: space-between; */
  display: grid;
  grid-template-columns: 3fr 1fr;
  
}
h1{
  text-align: center;
}
</style>
