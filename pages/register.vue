<template>
  <div>
    <div
      class="flex flex-col gap-8 max-w-4xl mx-auto p-10 justify-center h-screen"
    >
        <back-button to="/"></back-button>

        <logo class="animate-fade-in"></logo>
        <title-xl class="animate-fade-in" text="Register your account to a new Blog's World"></title-xl>
        <register-form></register-form>
            <go-to-login class="animate-fade-in"></go-to-login>
    </div>
  </div>
</template>

<script>
import BackButton from '~/components/Atoms/BackButton.vue'
import Logo from '~/components/Atoms/logo.vue'
import TitleXl from '~/components/Atoms/TitleXl.vue'
import GoToLogin from '~/components/Molecules/GoToLogin.vue'
import RegisterForm from '~/components/Organismis/RegisterForm.vue'
export default {
  components: { RegisterForm, GoToLogin, TitleXl, Logo, BackButton },

}
</script>

<style>

</style>