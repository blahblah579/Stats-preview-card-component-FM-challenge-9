<template>
  <v-app class="body">
    <v-main class="d-flex align-center justify-center">
      <HomePage />
    </v-main>
  </v-app>
</template>

<script setup>
import HomePage from "./components/HomePage.vue";
</script>

<style scoped>
.body {
  background-color: hsl(233, 46%, 7%);
}
</style>