<template>
  <div class="flex py-5 rounded-lg justify-between items-center">
    <logo></logo>
    <perfil-icon url="https://images.unsplash.com/photo-1570295999919-56ceb5ecca61?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8dXNlciUyMHByb2ZpbGV8ZW58MHx8MHx8&w=1000&q=80"></perfil-icon>
  </div>
</template>

<script>
import Logo from '../Atoms/logo.vue'
import PerfilIcon from '../Atoms/PerfilIcon.vue'
export default {
  components: { PerfilIcon, Logo },}
</script>

<style></style>
