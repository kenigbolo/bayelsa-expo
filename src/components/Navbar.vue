<template>
  <nav
    class="top-0 absolute z-50 w-full flex flex-wrap items-center justify-between px-2 py-0 md:py-3 navbar-expand-lg"
  >
    <div
      class="container px-4 mx-auto flex flex-wrap items-center justify-between"
    >
      <div
        class="w-full relative flex justify-between lg:w-auto lg:static lg:block lg:justify-start"
      >
        <a
          class="text-sm font-bold leading-relaxed inline-block mr-4 py-2 whitespace-no-wrap uppercase text-white"
          target="_blank"
          href="/"
        >
          <img
            alt="Bayelsa Science Fair Expo Logo"
            src="../assets/img/logo.png"
            class="max-w-full mx-auto"
            style="max-width: 120px;"
          />
        </a>
        <button
          class="cursor-pointer text-xl leading-none px-3 py-1 border border-solid border-transparent rounded bg-transparent block lg:hidden outline-none focus:outline-none"
          type="button"
          v-on:click="toggleNavbar()"
        >
          <i class="text-white fas fa-bars"></i>
        </button>
      </div>
      <div
        class="lg:flex flex-grow items-center bg-white lg:bg-transparent lg:shadow-none"
        v-bind:class="{ hidden: !showMenu, block: showMenu }"
      >
        <ul class="flex flex-col lg:flex-row list-none lg:ml-auto">
          <li class="flex items-center">
            <a
              class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
              target="_blank"
              href="https://www.facebook.com/bayelsaexpo/"
            >
            <i class="lg:text-gray-300 text-gray-500 fab fa-facebook text-lg leading-lg"></i>
            <span class="lg:hidden inline-block ml-2">Facebook Page</span>
            </a>
          </li>
          <li class="flex items-center">
            <a
              target="_blank"
              href="mailto:bayelsaexpo@gmail.com"
              class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
            >
              <i class="lg:text-gray-300 text-gray-500 fas fa-envelope text-lg leading-lg"></i>
              <span class="lg:hidden inline-block ml-2">Email</span>
            </a>
          </li>
          <li>
            <a
              target="_blank"
              href="https://chat.whatsapp.com/HNAi5WCUH1uChBGlWCdHh5"
              class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
            >
              <i class="lg:text-gray-300 text-gray-500 fab fa-whatsapp text-lg leading-lg"></i>
              <span class="lg:hidden inline-block ml-2">Whatsapp Chat</span>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<script>
export default {
  data() {
    return {
      showMenu: false,
    };
  },
  methods: {
    toggleNavbar: function() {
      this.showMenu = !this.showMenu;
    },
  },
};
</script>
