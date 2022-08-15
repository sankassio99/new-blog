<template>
  <div class="flex flex-col gap-10">
    <nav-bar></nav-bar>
    <title-xl text="Blogs"></title-xl>
    <search-field></search-field>
  </div>
</template>

<script>
import TitleXl from '../Atoms/TitleXl.vue'
import NavBar from '../Molecules/NavBar.vue'
import SearchField from '../Molecules/SearchField.vue'
export default {
  components: { NavBar, TitleXl, SearchField },
}
</script>

<style></style>
