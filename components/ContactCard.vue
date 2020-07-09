<template>
  <div>
    <a :href="href" target="_blank">
      <div
        class="bg-gray-300 hover:bg-gray-400 px-4 py-3 rounded-lg flex justify-between items-center shadow hover:shadow-lg text-gray-900 transition-prop"
        :class="classes"
      >
        <div>
          <div class="font-bold">{{title}}</div>
          <div>{{subTitle}}</div>
        </div>
        <div class="text-gray-800">
          <slot />
        </div>
      </div>
    </a>
  </div>
</template>

<script>
export default {
  props: ["href", "title", "subTitle", "classes"]
};
</script>

<style>
.transition-props {
  transition: all 0.3s;
}
</style>