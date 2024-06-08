<script setup>
import semilleros from '../data/semilleros.json'
</script>
<template>
  <div class="w-100 p-3 flex flex-wrap gap-8 content-center">
    <PrincipalSemilleros v-for="semillero in semilleros" :programa="semillero.programa" :facultad="semillero.facultad" :nombre="semillero.nombre"/>
  </div>
</template>
