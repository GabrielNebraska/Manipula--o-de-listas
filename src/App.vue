<script setup>
  import { ref } from 'vue'

  const Cidades = ref([
  {cidade: 'São Paulo', pais: 'Brasil'},
  {cidade:'Rio de Janeiro', pais: 'Brasil'},
  {cidade:'Belo Horizonte', pais: 'Brasil'},
  {cidade:'Salvador', pais: 'Brasil'},
  {cidade:'Fortaleza', pais: 'Brasil'},
  {cidade:'Curitiba', pais: 'Brasil'},
  {cidade:'Manaus', pais: 'Brasil'},
  {cidade:'Recife', pais: 'Brasil'},
  {cidade:'Porto Alegre', pais: 'Brasil'},
  {cidade:'Brasília', pais: 'Brasil'}
]);


</script>
<template>

  <ul>
    <li v-for="(cidade, index) in Cidades.value.sort()"> {{ cidade.value }} - {{ pais }}</li>
  </ul>

</template>

<style>


</style>
