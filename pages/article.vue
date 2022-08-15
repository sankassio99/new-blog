<template>
  <div class="max-w-3xl mx-auto px-6">
    <back-button to="/catalog"></back-button>
    <div class="mt-20">
      <banner-blog></banner-blog>
      <div class="my-16">
        <span class="text-gray-500 font-semibold"
          >By <span class="text-gray-900">Kelly Peter</span></span
        >
        <title-xl :text="'How to become master in colour palette?'"></title-xl>
      </div>
      <text-content></text-content>
    </div>
  </div>
</template>

<script>
import BackButton from '~/components/Atoms/BackButton.vue'
import Paragraph from '~/components/Atoms/Paragraph.vue'
import TitleXl from '~/components/Atoms/TitleXl.vue'
import BannerBlog from '~/components/Molecules/BannerBlog.vue'
import TextContent from '~/components/Molecules/TextContent.vue'
export default {
  components: { BackButton, BannerBlog, TitleXl, Paragraph, TextContent },
}
</script>

<style></style>
