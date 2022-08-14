<template>
  <div class="bg-gray-100 max-w-4xl max-h-96   rounded-xl overflow-hidden">
    <img :src="url" />
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
