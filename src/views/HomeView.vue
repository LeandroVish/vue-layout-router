<script setup>
import { useRouter } from 'vue-router'

const router = useRouter()

function goAbout() {
  router.push('/about')
}

</script>

<template>
  <h1>Home</h1>
  <button @click="goAbout"> Ir para Sobre </button>
  <button @click="$router.push('/help')"> Ir para Ajuda </button>
</template>

<style scoped></style>