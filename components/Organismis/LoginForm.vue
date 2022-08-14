<template>
  <form class="flex flex-col gap-8">
    <text-field inputType="email" :icon="'mail'" :placeholder="'Your email'"></text-field>
    <text-field inputType="password" :icon="'key'" :placeholder="'Your password'"></text-field>
    <base-button buttonType="submit" text="Login"></base-button>
  </form>
</template>

<script>
import BaseButton from '../Atoms/BaseButton.vue'
import TextField from '../Atoms/TextField.vue'
export default {
  components: { TextField, BaseButton },
}
</script>

<style>

</style>