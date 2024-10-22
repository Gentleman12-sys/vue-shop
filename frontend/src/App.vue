<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>

  <main>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </main>

  <RouterView />
</template>