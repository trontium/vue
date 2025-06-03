<template>
  <p>Using text interpolation: {{ rawHtml }}</p>
<p>Using v-html directive: <span v-html="rawHtml"></span></p>
</template>

<script lang="ts">
  export default {
    name: 'App',
  
  }

</script>

<style>

.app{
  background-color: #ddd;
  box-shadow:0 0 10px ;
  border-radius: 10px;
  padding: 20px;
}
</style>