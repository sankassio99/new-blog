<template>
  <form class="flex flex-col gap-8">
    <text-field
      class="animate-wiggle"
      inputType="email"
      :icon="'mail'"
      :placeholder="'Your email'"
    ></text-field>
    <text-field
      class="animate-wiggle"
      inputType="password"
      :icon="'key'"
      :placeholder="'Your password'"
    ></text-field>
    <base-button
      class="animate-wiggle-slow-1"
      to="/catalog"
      text="Login"
    ></base-button>
  </form>
</template>

<script>
import BaseButton from '../Atoms/BaseButton.vue'
import TextField from '../Atoms/TextField.vue'
export default {
  components: { TextField, BaseButton },
}
</script>

<style></style>
