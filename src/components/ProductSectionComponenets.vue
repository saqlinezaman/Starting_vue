<script setup></script>
<template>
    <section class="p-4 py-20">
    <div class="w-full max-w-7xl mx-auto">
      <div class="flex flex-col gap-8">
        <div class="flex flex-col lg:flex-row justify-between lg:items-center gap-4">
          <h2 class="text-3xl lg:text-5xl pb-4">
            Featured products
          </h2>
          <div class="flex gap-4 text-xl">
            <a href="" class="p-2 px-4 border border-black hover:bg-black hover:text-white rounded-full">
              All
            </a>
            <a href="" class="p-2 px-4 border border-black bg-black text-white rounded-full">
              New arrival
            </a>
            <a href="" class="p-2 px-4 border border-black hover:bg-black hover:text-white rounded-full">
              Best seller
            </a>
          </div>
        </div>

        <div class="flex gap-4">
          <a href="" class="w-full flex flex-col gap-2">
            <div class="max-h-[300px] md:max-h-[400px] overflow-hidden rounded-xl shadow-xl relative">
              <i
                class="flex items-center justify-center text-white rounded-full bg-black p-2 bi bi-arrow-up-right absolute top-4 right-4"></i>
              <img class="w-full"
                src="https://images.unsplash.com/photo-1566206091558-7f218b696731?q=80&w=3464&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                alt="">
            </div>
            <h3 class="text-2xl pt-4 flex flex-col lg:flex-row lg:items-center">White dress <span
                class="lg:ml-auto text-yellow-700 font-bold">240$</span></h3>
            <div class="flex gap-2">
              <div class="rounded-full w-[20px] h-[20px] bg-white border shadow"></div>
              <div class="rounded-full w-[20px] h-[20px] bg-gray-200 border shadow"></div>
            </div>
          </a>
          <a href="" class="w-full flex flex-col gap-2">
            <div class="max-h-[300px] md:max-h-[400px] overflow-hidden rounded-xl shadow-xl relative">
              <i
                class="flex items-center justify-center text-white rounded-full bg-black p-2 bi bi-arrow-up-right absolute top-4 right-4"></i>
              <img class="w-full"
                src="https://images.unsplash.com/photo-1608748010899-18f300247112?q=80&w=3464&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                alt="">
            </div>
            <h3 class="text-2xl pt-4 flex flex-col lg:flex-row lg:items-center">Brown dress <span
                class="lg:ml-auto text-yellow-700 font-bold">629.99$</span></h3>
            <div class="flex gap-2">
              <div class="rounded-full w-[20px] h-[20px] bg-amber-800 border shadow"></div>
              <div class="rounded-full w-[20px] h-[20px] bg-orange-200 border shadow"></div>
            </div>
          </a>
          <a href="" class="w-full hidden md:flex flex-col gap-2">
            <div class="max-h-[300px] md:max-h-[400px] overflow-hidden rounded-xl shadow-xl relative">
              <i
                class="flex items-center justify-center text-white rounded-full bg-black p-2 bi bi-arrow-up-right absolute top-4 right-4"></i>
              <img class="w-full"
                src="https://images.unsplash.com/photo-1625204614387-6509254d5b02?q=80&w=3024&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                alt="">
            </div>
            <h3 class="text-2xl pt-4 flex flex-col lg:flex-row lg:items-center">Lorem dress <span
                class="lg:ml-auto text-yellow-700 font-bold">742.30$</span></h3>
            <div class="flex gap-2">
              <div class="rounded-full w-[20px] h-[20px] bg-pink-600 border shadow"></div>
              <div class="rounded-full w-[20px] h-[20px] bg-lime-500 border shadow"></div>
            </div>
          </a>
        </div>

        <a href="" class="p-2 px-4 border border-black hover:bg-black hover:text-white rounded-full mx-auto text-xl">
          See all products <i class="bi bi-arrow-up-right"></i>
        </a>
      </div>
    </div>
  </section>
</template>
<style scoped></style>