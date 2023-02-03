<script setup>
const { text, desc, className } = defineProps([
  'text',
  'desc',
  'className',
]);
</script>

<template>
  <h4>{{ text }}</h4>
  <p v-bind:class="className ? className : ''">{{ desc }}</p>
</template>
