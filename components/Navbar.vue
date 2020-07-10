<template>
  <header
    class="bg-white dark:bg-black bg-opacity-75 dark:bg-opacity-75 backdrop-blur fixed w-full shadow z-10"
  >
    <div
      class="container px-4 lg:px-6 xl:px-10 flex flex-wrap justify-between items-center py-2 mx-auto"
    >
      <a href="#" class="text-2xl font-bold">Kunal Gosrani</a>
      <input type="checkbox" id="check" class="hidden" v-model="menuShow" />
      <label for="check" class="float-right sm:hidden cursor-pointer dark-invert">
        <svg width="1.5em" height="1.5em" viewBox="0 0 16 16">
          <path
            fill-rule="evenodd"
            d="M1.646 6.646a.5.5 0 0 1 .708 0L8 12.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z"
          />
          <path
            fill-rule="evenodd"
            d="M1.646 2.646a.5.5 0 0 1 .708 0L8 8.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z"
          />
        </svg>
      </label>
      <div class="sm:hidden w-0 break-column"></div>
      <nav class="text-center mx-auto sm:m-0">
        <ul>
          <li
            v-for="(el, index) in navElements"
            :key="index"
            class="w-full sm:w-auto sm:inline-block py-1 sm:py-0 sm:px-2"
          >
            <a :href="el.link" @click="hideMenu">
              <Button class="hover:bg-gray-200 dark:hover:bg-gray-800" type="basic">{{el.name}}</Button>
            </a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
import Button from "./Button";

export default {
  components: {
    Button
  },
  data() {
    return {
      menuShow: false,
      navElements: [
        { name: "About", link: "#about" },
        { name: "Work", link: "#work" },
        { name: "Contact", link: "#contact" }
      ]
    };
  },
  methods: {
    hideMenu() {
      this.menuShow = false;
    }
  }
};
</script>

<style scoped>
ul {
  list-style: none;
}

.break-column {
  flex-basis: 100%;
}

@media (max-width: 639.99px) {
  nav {
    display: none;
    transition: all 0.3s;
  }

  #check:checked ~ nav {
    display: block;
  }
}
</style>