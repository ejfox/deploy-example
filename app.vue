<template>
  <div>
    <h1>{{msg}}</h1>

    <!-- when button is clicked, change message to 'hello world!' -->
    <button @click="msg = 'hello world!'">change message</button>
    
  </div>
</template>
<script setup>
const msg = ref('Hello deploy')
</script>
<style>
h1 {
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 8rem;
}
</style>