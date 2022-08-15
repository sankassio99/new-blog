<template>
  <div class="bg-gray-100 w-60 h-40 rounded-xl overflow-hidden">
    <div class="bg-white w-12 h-6 rounded-xl absolute m-4">
        <span class="text-center text-xs text-gray-600 font-semibold px-2">3 Feb</span>
    </div>
    <img :src="url" class="w-full object-cover" />
  </div>
</template>

<script> 
export default {
  props: {
    url: {
        type: String,
        required: false,
    },
  },
}
</script>

<style></style>
