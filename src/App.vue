<script setup lang="ts">
import { ref } from 'vue';

const test = ref<boolean>(false);
</script>

<template>
  <header>
    <a href="#">Cursos</a>
    {{ test }}
    <a href="#">Cursos</a>
  </header>
</template>
