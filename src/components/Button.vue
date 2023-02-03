<script setup>
const props = defineProps(['type', 'text', 'handleClick']);
</script>
<template>
  <button v-bind:="props" @click="handleClick">
    {{ props.text }}
  </button>
</template>
