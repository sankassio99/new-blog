<template>
  <div>
    <div
      class="flex flex-col gap-8 max-w-4xl mx-auto p-10 justify-center h-screen"
    >
        <back-button to="/"></back-button>
        <logo></logo>
        <title-xl text="Login with your account and fun"></title-xl>
        <login-form></login-form>

        <go-to-register></go-to-register>

    </div>
  </div>
</template>

<script>
import BackButton from '~/components/Atoms/BackButton.vue'
import Logo from '~/components/Atoms/logo.vue'
import TitleXl from '~/components/Atoms/TitleXl.vue'
import GoToRegister from '~/components/Molecules/GoToRegister.vue'
import LoginForm from '~/components/Organismis/LoginForm.vue'
export default {
  components: { LoginForm, GoToRegister, TitleXl, Logo, BackButton },

}
</script>

<style>

</style>