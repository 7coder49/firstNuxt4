<template>
  <nav style="width: 100%; background: #333; color: #fff; padding: 1rem 0; display: flex; justify-content: center; gap: 2rem;">
    <NuxtLink to="/" style="color: #fff; text-decoration: none; font-weight: bold;"
      :style="{'text-decoration': route.path === '/' ? 'underline' : 'none'}" class="cursor-pointer">Index</NuxtLink>
    <NuxtLink to="/home" style="color: #fff; text-decoration: none; font-weight: bold;"
      :style="{'text-decoration': route.path === '/home' ? 'underline' : 'none'}" class="cursor-pointer">Home</NuxtLink>
  </nav>
  <slot />
</template>

<script setup>
const route = useRoute();
</script>
<style lang="scss">
nav {
  height: 3.25rem;
}
</style>