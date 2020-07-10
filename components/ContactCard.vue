<template>
  <div>
    <a :href="href" target="_blank">
      <div
        class="text-gray-900 dark:text-gray-100 bg-gray-300 dark:bg-gray-800 hover:bg-gray-400 dark:hover:bg-gray-700 px-4 py-3 rounded-lg flex justify-between items-center shadow hover:shadow-lg"
        :class="classes"
      >
        <div>
          <div class="font-bold">{{title}}</div>
          <div class="text-gray-800 dark:text-gray-200">{{subTitle}}</div>
        </div>
        <div class="text-gray-800 dark:text-gray-200">
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
a > div {
  transition: all 0.3s;
}
</style>