<template>
  <section class="relative py-20">
    <div
      class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20"
      style="height: 80px; transform: translateZ(0px);"
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
          class="text-white fill-current"
          points="2560 0 2560 100 0 100"
        ></polygon>
      </svg>
    </div>
    <div class="container mx-auto px-4">
      <div class="items-center flex flex-wrap">
        <div class="w-full md:w-5/12 ml-auto mr-auto px-4">
          <div class="md:pr-12">
            <div
              class="text-gray-600 p-3 mt-2 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-gray-300"
            >
              <i class="fas fa-layer-group text-xl"></i>
            </div>
            <h3 class="text-3xl font-semibold">Project Categories</h3>
            <ul class="list-none mt-6">
              <li class="py-2">
                <div class="flex items-center">
                  <div>
                    <span
                      class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-gray-600 bg-gray-200 mr-3"
                      ><i class="fas fa-tools"></i
                    ></span>
                  </div>
                  <div>
                    <h4 class="text-gray-600">
                      Engineering / Computer Science
                    </h4>
                  </div>
                </div>
              </li>
              <li class="py-2">
                <div class="flex items-center">
                  <div>
                    <span
                      class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-gray-600 bg-gray-200 mr-3"
                      ><i class="fas fa-vials"></i
                    ></span>
                  </div>
                  <div>
                    <h4 class="text-gray-600">
                      Scientific Research
                    </h4>
                  </div>
                </div>
              </li>
              <li class="py-2">
                <div class="flex items-center">
                  <div>
                    <span
                      class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-gray-600 bg-gray-200 mr-3"
                      ><i class="fas fa-calculator"></i
                    ></span>
                  </div>
                  <div>
                    <h4 class="text-gray-600">
                      Mathematics Olympiad
                    </h4>
                  </div>
                </div>
              </li>
              <li class="py-2">
                <div class="flex items-center">
                  <div>
                    <span
                      class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-gray-600 bg-gray-200 mr-3"
                    >
                      <i class="fas fa-file-medical-alt"></i>
                    </span>
                  </div>
                  <div>
                    <h4 class="text-gray-600">
                      Medical / Biomedical Science
                    </h4>
                  </div>
                </div>
              </li>
              <li class="py-2">
                <div class="flex items-center">
                  <div>
                    <span
                      class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-gray-600 bg-gray-200 mr-3"
                      ><i class="fas fa-user-friends"></i
                    ></span>
                  </div>
                  <div>
                    <h4 class="text-gray-600">
                      Social Science
                    </h4>
                  </div>
                </div>
              </li>
            </ul>
          </div>
        </div>
        <div class="w-full md:w-4/12 ml-auto mr-auto px-4">
          <img
            alt="..."
            class="max-w-full rounded-lg shadow-lg"
            src="https://images.unsplash.com/photo-1578496479531-32e296d5c6e1?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=668&q=80"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>
