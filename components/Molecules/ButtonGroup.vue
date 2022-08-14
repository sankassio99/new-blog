<template>
  <div class="flex gap-2">
    <base-button :to="'register'" text="Register"></base-button>
    <outline-button :to="'login'" text="Login" @click="alert('teste')"></outline-button>
  </div>
</template>

<script>
import BaseButton from '../Atoms/BaseButton.vue'
import OutlineButton from '../Atoms/OutlineButton.vue'
export default {
  components: { BaseButton, OutlineButton },
}
</script>

<style></style>
