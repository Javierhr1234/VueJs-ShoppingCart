<script setup>
import { ref } from 'vue' ;
const header = ref ('Mi carrito de compras')
</script>

<template>
  <h1> <i class ="material-icons shopping-cart-icon" >local_mall</i>{{ header }} </h1>
</template>

<style scoped>
.shoppind-cart-icon{
  font-size: 2rem;

}
</style>
