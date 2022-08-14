<template>
  <div class="max-w-4xl mx-auto p-10 h-screen flex flex-col justify-between">
    <header-one></header-one>
    <div
      class="flex flex-col gap-8 lg:gap-16 justify-end"
    >
      <div class="w-96">
        <welcome-title></welcome-title>
      </div>
      <button-group></button-group>
      <keep-with-phone></keep-with-phone>
    </div>
  </div>
</template>

<script>
import ButtonGroup from '~/components/Molecules/ButtonGroup.vue'
import HeaderOne from '~/components/Molecules/HeaderOne.vue'
import KeepWithPhone from '~/components/Molecules/KeepWithPhone.vue'
import WelcomeTitle from '~/components/Molecules/WelcomeTitle.vue'

export default {
  components: { ButtonGroup, WelcomeTitle, KeepWithPhone, HeaderOne },
}
</script>

<style></style>
