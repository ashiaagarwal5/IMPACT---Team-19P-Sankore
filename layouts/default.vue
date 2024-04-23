<script setup lang = "ts">
    import Navbar from "../components/layout/navbar.vue";
</script>

<template>
    <div class="flex flex-col justify-between h-screen">
      <Navbar />
      <div class="flex-grow">
        <slot />
      </div>
    </div>
  </template>
  