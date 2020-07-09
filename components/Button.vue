<template>
  <button
    class="btn font-semibold"
    :class="{'shadow':type != 'basic', ' hover:shadow-lg':type != 'basic'}"
  >
    <slot />
  </button>
</template>

<script>
export default {
  props: ["type"]
};
</script>

<style>
button {
  transition: all 0.3s ease 0s;
}
</style>