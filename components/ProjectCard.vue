<template>
  <div>
    <a target="_blank">
      <div
        class="bg-cover bg-center rounded-lg p-1 card shadow-md"
        :class="classes"
        :style="'background-image: url(' + imageUrl + ');'"
      >
        <div class="h-40"></div>
        <div
          class="content bg-gray-200 dark:bg-gray-800 bg-opacity-75 dark:bg-opacity-75 backdrop-blur m-1 p-2 pl-3 pr-0 overflow-hidden rounded-lg flex justify-between items-center"
        >
          <div>
            <div class="font-bold">{{title}}</div>
            <div class="text-sm">{{subtitle}}</div>
          </div>
          <div>
            <a :href="link" target="_blank">
              <Button
                class="bg-opacity-0 text-gray-900 dark:text-gray-100 shadow-none hover:shadow-none"
              >
                <svg
                  width="1.5em"
                  height="1.5em"
                  viewBox="0 0 16 16"
                  fill="currentColor"
                  class="icon"
                >
                  <path
                    fill-rule="evenodd"
                    d="M1.5 13A1.5 1.5 0 0 0 3 14.5h8a1.5 1.5 0 0 0 1.5-1.5V9a.5.5 0 0 0-1 0v4a.5.5 0 0 1-.5.5H3a.5.5 0 0 1-.5-.5V5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 0 0-1H3A1.5 1.5 0 0 0 1.5 5v8zm7-11a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-1 0V2.5H9a.5.5 0 0 1-.5-.5z"
                  />
                  <path
                    fill-rule="evenodd"
                    d="M14.354 1.646a.5.5 0 0 1 0 .708l-8 8a.5.5 0 0 1-.708-.708l8-8a.5.5 0 0 1 .708 0z"
                  />
                </svg>
              </Button>
            </a>
          </div>
        </div>
      </div>
    </a>
  </div>
</template>

<script>
import Button from "./Button";

export default {
  components: {
    Button
  },
  props: ["imageUrl", "title", "subtitle", "link", "classes"]
};
</script>

<style>
a > div {
  transition: all 0.3s;
}
/* 
.content {
  -webkit-backdrop-filter: saturate(180%) blur(20px);
  backdrop-filter: saturate(180%) blur(7px) !important;
} */

.card {
  border-radius: 12px;
}
</style>