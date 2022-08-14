<template>
  <div class="flex flex-col">
    <div class="max-w-3xl">
      <banner
        url="https://images.unsplash.com/photo-1503023345310-bd7c1de61c7d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8aHVtYW58ZW58MHx8MHx8&w=1000&q=80"
      ></banner>
      <div class="flex justify-between">
        <div></div>
        <bookmark-button style="margin-top: -10px" class=""></bookmark-button>
      </div>
    </div>
  </div>
</template>

<script>
import Banner from '../Atoms/Banner.vue'
import BookmarkButton from '../Atoms/BookmarkButton.vue'
export default {
  components: { Banner, BookmarkButton },
}
</script>

<style></style>
