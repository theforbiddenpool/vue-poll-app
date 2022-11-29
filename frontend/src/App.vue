<script setup>
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
  <header>
    <nav>
      <RouterLink to="/">Home</RouterLink>
    </nav>
  </header>

  <RouterView />
</template>

<style lang="scss" scoped>
header {
  width: 100%;
  padding: 1em;
}

nav a.router-link-exact-active {
  color: green;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
}
</style>
