<template>
  <div class="">
    <p
      class="font-medium text-gray-400 first-letter:text-7xl first-letter:text-gray-900 first-letter:float-left first-letter:mr-2"
    >
      {{ text }}
    </p>
  </div>
</template>

<script>
export default {
  props: {
    text: {
      type: String,
      required: true,
    },
  },
}
</script>

<style></style>
