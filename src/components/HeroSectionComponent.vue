<script setup>
import rating from './rating.vue';
</script>
<template>
 <section class="p-4 py-10" data-aos="fade-down" data-aos-duration="1000">
    <div class="w-full max-w-7xl mx-auto">
      <div class="flex flex-col gap-10 items-center">
        <rating count="3" text="4.8k"/>
        <h1 class="text-2xl lg:text-5xl text-center">
          Ethical Fashion: Elegant & Sustainable
          <span class="block text-gray-400 pt-4">Enhancing Your Style</span>
        </h1>
        <div class="flex flex-col md:flex-row items-center gap-4">
          <a href="" class="bg-black border border-black text-white rounded-lg p-2 px-8 shadow-xl outline-none">Check
            our collections</a>
          <a href="" class="border border-black text-black rounded-lg p-2 px-8 shadow-xl outline-none">Sales</a>
        </div>
      </div>
    </div>
  </section>
</template>
<style scoped>
</style>