<script setup>
import { RouterView } from "vue-router";
import TheHeader from "./components/TheHeader.vue";
</script>

<template>
  <TheHeader />
  <RouterView />
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Abel&family=Dosis:wght@300;400;500;700&display=swap");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Abel", sans-serif;
}
.container {
  max-width: 1100px;
  margin: 0 auto;
}
</style>
