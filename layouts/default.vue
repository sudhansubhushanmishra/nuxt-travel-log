<script setup lang="ts">
import NavBar from "~/components/app/nav-bar.vue";
</script>

<template>
  <div class="flex min-h-screen flex-col">
    <NavBar />
    <main>
      <slot />
    </main>
  </div>
</template>
