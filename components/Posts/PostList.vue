<template>
  <section class="featured-posts">
    <PostPreview id="1" title="First Title" preview-text="First Preview" thumbnail="" />
    <PostPreview id="2" title="First Title 2" preview-text="Preview 2" thumbnail="" />
    <PostPreview id="3" title="First Title 3" preview-text="Preview 3" thumbnail="" />
  </section>
</template>

<script>
import PostPreview from './PostPreview'

export default {
  components: {
    PostPreview
  }
}
</script>
<style scoped>
.featured-posts {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>
