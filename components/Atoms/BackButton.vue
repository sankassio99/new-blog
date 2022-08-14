<template>
  <div class="absolute top-3">
    <button @click="navigate"
      class="base-button bg-white pt-2 pb-2 px-3 w-12 rounded-full hover:bg-gray-100"
    >
      <span class="material-icons"> arrow_back </span>
    </button>
  </div>
</template>

<script>
export default {
  props: {
    to: {
      type: String,
      required: false,
    },
  },
  methods: {
    navigate() {
      if (this.to) {
        this.$router.push({
          path: this.to,
        })
      }
    },
  },
}
</script>

<style></style>
