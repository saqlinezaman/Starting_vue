<script setup>
defineProps(['count' , 'text'])
</script>
<template>
    <div class="flex gap-4 items-center">
          <div class="flex gap-1">
            <i v-for="index in Math.ceil(count)" :key="index"  class="bi bi-star-fill text-yellow-400"></i>
          </div>
          <span class="text-xs text-gray-600">
           {{ count }}/5 ({{ text  }} Reviews)
          </span>
        </div>
</template>
<style scoped></style>