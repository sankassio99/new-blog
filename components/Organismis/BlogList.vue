<template>
  <div class="flex flex-col gap-8 my-12">
    <blog-item to="/article"></blog-item>
    <blog-item></blog-item>
    <blog-item></blog-item>
  </div>
</template>

<script>
import BlogItem from '../Molecules/BlogItem.vue'
export default {
  components: { BlogItem },
}
</script>

<style></style>
