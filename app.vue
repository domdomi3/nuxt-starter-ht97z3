<template>
  <div>Hello world!</div>
</template>

<script setup lang="ts">
const r = useRoute();

useHead({
  title: r.query.title as string,
});
</script>
