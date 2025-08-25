<template>
  <nav style="width: 100%; background: #333; color: #fff; padding: 1rem 0; display: flex; justify-content: center; gap: 2rem;">
    <NuxtLink to="/" style="color: #fff; text-decoration: none; font-weight: bold;">Home</NuxtLink>
    <NuxtLink to="/home" style="color: #fff; text-decoration: none; font-weight: bold;">Table</NuxtLink>
  </nav>
  <slot />
</template>

<script setup>
// No script needed for simple layout
</script>
