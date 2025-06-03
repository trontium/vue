<template>
  <h1 :class='titleClass'> Make me red</h1>
</template>

<script setup>
  import { ref } from 'vue'
  const titleClass =ref('title')

</script>

<style>

.app{
  background-color: #ddd;
  box-shadow:0 0 10px ;
  border-radius: 10px;
  padding: 20px;
}
</style>