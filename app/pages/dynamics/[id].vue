<template>
  <div id="dynamics-container" style="display: flex; flex-direction: column; align-items: center; justify-content: center; background: #f8f9fa;">
    <h1 style="margin-bottom: 2rem;">Dynamic Page</h1>
    <p>This is a dynamic page. The id is: {{ $route.params.id }}</p>
  </div>
</template>

<script setup lang="ts">
// definePageMeta({
//   validate: async (route) => {
//     return typeof route.params.id === 'string' && /^\d+$/.test(route.params.id);
//   }
// })
</script>

<style lang="scss">
#dynamics-container {
  height: calc(100vh - 3.25rem);
}
</style>
