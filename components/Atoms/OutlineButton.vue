<template>
  <button @click="navigate" :type="buttonType" class="outline-button border py-2 w-full rounded-full hover:bg-gray-200">
     <span class="text-gray-800">{{ text }}</span> 
  </button>
</template>

<script> 
export default {
  props: {
    text: {
      type: String,
      required: true,
    },
    buttonType: {
      type: String,
      default: 'button',
      required: false,
    },
    to: {
      type: String,
      required: false,
    }
  },
  methods:{
    navigate() {
      if (this.to) {
        this.$router.push({
          path: this.to,
        })
      }
    },
  }
}
</script>

<style></style>
