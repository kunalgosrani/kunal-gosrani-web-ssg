<template>
  <button class="btn font-semibold">
    <slot />
  </button>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>

<style>
button {
  transition: all 0.3s ease 0s;
}
</style>