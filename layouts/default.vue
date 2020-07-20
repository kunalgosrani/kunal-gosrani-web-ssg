<template>
  <div
    class="bg-gray-100 text-gray-900 dark:bg-gray-900 dark:text-gray-100 w-full overflow-x-hidden"
  >
    <Navbar />
    <Nuxt class="pt-16" />
  </div>
</template>

<style>
html {
  word-spacing: 1px;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>

<script>
import Navbar from "../components/Navbar";

export default {
  components: {
    Navbar
  }
};
</script>