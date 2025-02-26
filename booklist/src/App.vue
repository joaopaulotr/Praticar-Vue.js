<script setup>

  let count = 0;

</script>

<template>
  <div>
    
    <h1>{{ count }}</h1>
    <button @click="count++ ">Incrementar +</button>

  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>

</style>
