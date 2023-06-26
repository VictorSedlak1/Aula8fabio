<script setup></script>

<template>
  <h1>Home</h1>
  <button @click="$router.push({name:'about'})">Ir para sobre</button>
  <button @click="$router.push({name:'peticao'})">Ir para Petição</button>
</template>
