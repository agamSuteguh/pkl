<template>
  <div
    class="w-full h-full md:h-auto grid grid-cols-1 md:grid-cols-3 gap-4 px-2 py-4"
  >
    <!-- item 1 -->
    <div class="select-none mb-6 w-full">
      <div class="relative pb-64">
        <a href="#" class="cursor-pointer">
          <img
            class="absolute w-full h-full rounded-lg object-cover border-b shadow-md cursor-pointer"
            src="https://images.unsplash.com/photo-1574920162043-b872873f19c8?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=600&q=80"
            alt="product name"
          />
        </a>
      </div>

      <div class="px-4 -mt-16 relative">
        <div class="bg-white rounded-lg shadow-lg border">
          <div class="p-5">
            <div class="flex justify-between items-center">
              <div class="opacity-75 text-xs">
                <a class="hover:underline" href="#"> Apple </a>
              </div>

              <span
                class="text-green-500 rounded-full bg-sisa-200 px-3 py-1 text-xs select-none"
              >
                Tersisa 4
              </span>
            </div>

            <a
              class="text-gray-800 block mt-2 truncate hover:underline font-medium text-lg"
              href="#"
            >
              Apple Airpods
            </a>
          </div>

          <div class="flex justify-between items-center pb-3 px-4">
            <div>
              <div class="text-gray-800 text-lg">
                <span class="font-medium">RP 24900</span>
              </div>
            </div>

            <div>
              <a
                class="btn-link flex items-center text-xs text-indigo-600 hover:underline"
                href="#"
              >
                View Product &rarr;
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
