<template>
  <div class="bg-gray-100 w-72 h-40 rounded-xl overflow-hidden" style="min-width: 149px;">
    <div class="bg-white w-12 h-6 rounded-xl absolute m-4">
        <span class="text-xs text-gray-600 font-semibold w-12 flex justify-center pt-1">3 Feb</span>
    </div>
    <img :src="url" class="w-full object-fill" />
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
