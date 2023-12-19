<template>
    <div>
      <h1>This is my component</h1>
      <h2>{{ title }}</h2>
    </div>
  </template>
  
  <script lang ="ts" setup>
  import { ref } from 'vue';
  
  const title = ref('Hello, world!');

  </script>
  
  <style scoped>
  h1 {
    color: red;
  }
  </style>
  