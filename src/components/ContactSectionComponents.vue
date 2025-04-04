<script setup>
</script>
<template>
    <section class="p-4 py-20">
    <div class="mx-auto max-w-7xl w-full">
      <div class="grid lg:grid-cols-2 grid-cols-1 items-center">
        <div class="lg:mb-0 mb-10">
          <div class="group w-full h-full">
            <div class="relative h-full">
              <img
                src="https://images.unsplash.com/photo-1516762689617-e1cffcef479d?q=80&w=3711&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                alt="ContactUs tailwind section" class="w-full h-full lg:rounded-l-2xl rounded-2xl bg-blend-multiply" />
              <h1 class="font-manrope text-black text-4xl font-bold leading-10 absolute top-11 left-11">Contact us</h1>
              <div class="absolute bottom-0 w-full lg:p-11 p-5">
                <div class="bg-white rounded-lg p-6 block">
                  <a href="#" class="flex items-center mb-6">
                    <i class="bi bi-telephone"></i>
                    <h5 class="underline text-black text-base font-normal leading-6 ml-5">123-123-123</h5>
                  </a>
                  <a href="mailto:pro@lingare.com" class="flex items-center mb-6">
                    <i class="bi bi-envelope"></i>
                    <h5 class="underline text-black text-base font-normal leading-6 ml-5">pro@email.com</h5>
                  </a>
                  <a href="#" class="flex items-center">
                    <i class="bi bi-geo-alt"></i>
                    <h5 class="underline text-black text-base font-normal leading-6 ml-5">424 Yallala Avenue,
                      Meadowville, WA
                      76543</h5>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="p-5 lg:p-11 lg:rounded-r-2xl rounded-2xl">
          <h2 class="font-manrope text-4xl font-semibold leading-10 mb-11">Send Us A Message</h2>
          <input type="text"
            class="w-full h-12 text-gray-600 placeholder-gray-400  shadow-sm bg-transparent text-lg font-normal leading-7 border border-black focus:outline-none p-4 mb-10"
            placeholder="Name">
          <input type="text"
            class="w-full h-12 text-gray-600 placeholder-gray-400 shadow-sm bg-transparent text-lg font-normal leading-7 border border-black focus:outline-none p-4 mb-10"
            placeholder="Email">
          <input type="text"
            class="w-full h-12 text-gray-600 placeholder-gray-400 shadow-sm bg-transparent text-lg font-normal leading-7 border border-black focus:outline-none p-4 mb-10"
            placeholder="Phone">
          <textarea
            class="max-h-[200px] w-full text-gray-600 placeholder-gray-400 bg-transparent text-lg shadow-sm font-normal leading-7 border border-black focus:outline-none p-4 mb-10"
            placeholder="Message"></textarea>
          <button
            class="w-full h-12 text-white text-base font-semibold leading-6 rounded-full transition-all duration-700 bg-black shadow-sm">Send</button>
        </div>
      </div>
    </div>
  </section>
</template>
<style scoped></style>