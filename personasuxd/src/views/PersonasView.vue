<script setup>
import personas from '../components/Personas.vue'
</script>

<template>
  <main class="fondo2">
    <personas/>
  </main>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
.fondo2
{
  background-color:#758fc2bf;
  width: 100%;
  display: inline-flex;
}

</style>