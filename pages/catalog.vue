<template>
  <div class="max-w-3xl mx-auto px-5">
    <header-main></header-main>
    <blog-list></blog-list>
  </div>
</template>

<script>
import HeaderMain from '~/components/Organismis/HeaderMain.vue'
import SearchField from '~/components/Molecules/SearchField.vue'
import BlogList from '~/components/Organismis/BlogList.vue'
export default {
  components: { SearchField, HeaderMain, BlogList },

}
</script>

<style>

</style>