<template>
  <div
    class="relative pt-24 md:pt-16 pb-32 flex content-center items-center justify-center"
    style="min-height: 75vh;"
  >
    <div
      class="absolute top-0 w-full h-full bg-center bg-cover"
      style='background-image: url("https://images.unsplash.com/photo-1572456556351-fb3d2fbd75e6?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1350&q=80");'
    >
      <span
        id="blackOverlay"
        class="w-full h-full absolute opacity-75 bg-black"
      ></span>
    </div>
    <div class="container relative mx-auto">
      <div class="items-center flex flex-wrap">
        <div class="w-full lg:w-8/12 px-4 ml-auto mr-auto text-center">
          <div>
            <h1 class="text-white font-semibold text-5xl">
              Festival of Science and Technology
            </h1>
            <h2 class="text-white font-semibold text-2xl py-2">
              March 5th - 6th, 2021
            </h2>
            <h3 class="text-white font-semibold text-xl py-2">
              Gabriel Okara Cultural Center, Yenagoa, Bayelsa State
            </h3>
            <p class="mt-4 text-lg text-gray-300">
              Bayelsa Expo is designed to inspire and prepare young Bayelsans to
              succeed, lead and innovate in Science, Technology, Engineering,
              Arts and Mathematics (STEAM) fields and beyond
            </p>
          </div>
        </div>
      </div>
    </div>
    <div
      class="top-auto bottom-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden"
      style="height: 70px; transform: translateZ(0px);"
    >
      <svg
        class="absolute bottom-0 overflow-hidden"
        xmlns="http://www.w3.org/2000/svg"
        preserveAspectRatio="none"
        version="1.1"
        viewBox="0 0 2560 100"
        x="0"
        y="0"
      >
        <polygon
          class="text-gray-300 fill-current"
          points="2560 0 2560 100 0 100"
        ></polygon>
      </svg>
    </div>
  </div>
</template>

<script>
export default {};
</script>
