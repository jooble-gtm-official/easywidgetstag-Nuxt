<template>
  <div class="test-container">
    <img :alt="image_alt" :src="image_src" class="test-image" />
  </div>
</template>

<script>
export default {
  name: 'Test',
  props: {
    image_src: {
      type: String,
      default: '/mf-400h.png',
    },
    image_alt: {
      type: String,
      default: 'image',
    },
  },
}
</script>

<style scoped>
.test-container {
  width: 100%;
  height: 400px;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.test-image {
  width: 200px;
  object-fit: cover;
}
</style>
