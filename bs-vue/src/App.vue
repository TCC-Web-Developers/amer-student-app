<script setup>
import { RouterView } from "vue-router";
</script>

<template>
  <RouterView />
</template>

<style lang="scss">
@import "./assets/scss/custom.scss";
@import url("https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;700&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@100;400;700&display=swap");

body,
span {
  font-family: "Roboto", sans-serif;
}
h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Playfair Display", serif;
}
</style>
