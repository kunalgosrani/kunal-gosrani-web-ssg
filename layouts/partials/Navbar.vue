<template>
  <header
    class="flex flex-wrap justify-between items-center px-4 sm:px-10 md:px-20 py-2 bg-white bg-opacity-75 fixed w-full"
  >
    <nuxt-link to="/" class="text-2xl font-bold">Kunal Gosrani</nuxt-link>
    <input type="checkbox" id="check" class="hidden" />
    <label for="check" class="float-right sm:hidden">
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
          <a :href="el.link">
            <Button class="hover:bg-gray-200 text-gray-900" type="basic">{{el.name}}</Button>
          </a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
import Button from "../../components/Button";

export default {
  components: {
    Button
  },
  data() {
    return {
      navElements: [
        { name: "About", link: "#about" },
        { name: "Work", link: "#work" },
        { name: "Contact", link: "#contact" }
      ]
    };
  }
};
</script>

<style scoped>
ul {
  list-style: none;
}

header {
  /* background-opacity: 80%; */
  -webkit-backdrop-filter: saturate(180%) blur(20px);
  backdrop-filter: saturate(180%) blur(20px) !important;
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