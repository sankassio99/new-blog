<template>
  <nuxt-link :to="to" class="flex items-center gap-6">
    <front-cover class="animate-wiggle"
      url="https://images.pexels.com/photos/3952150/pexels-photo-3952150.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500"
    ></front-cover>
    <div class="desc flex flex-col gap-4 animate-wiggle-slow-1">
      <span class="text-sm text-gray-400 font-semibold">05 mins read</span>
      <title-lg :text="'Make design system people want to use'"></title-lg>
      <div class="flex gap-3 ">
        <like-counter></like-counter>
        <comments-counter></comments-counter>
      </div>
    </div>
  </nuxt-link>
</template>

<script>
import CommentsCounter from '../Atoms/CommentsCounter.vue'
import FrontCover from '../Atoms/FrontCover.vue'
import LikeCounter from '../Atoms/LikeCounter.vue'
import TitleLg from '../Atoms/TitleLg.vue'
export default {
  components: { FrontCover, TitleLg, LikeCounter, CommentsCounter },
  props: {
    to: {
      type: String,
      required: false,
      default: '#'
    },
  },
}
</script>

<style></style>
