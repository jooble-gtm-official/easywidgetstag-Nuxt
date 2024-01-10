<template>
  <div class="mf-test-container">
    <span class="mf-test-text">Module Federation Test</span>
    <img :alt="image_alt" :src="image_src" class="mf-test-image" />
    <button
      type="button"
      @click="this.$emit('onClick')"
      class="mf-test-button button"
    >
      Apply
    </button>
  </div>
</template>

<script>
export default {
  name: 'MfTest',
  props: {
    image_src: {
      type: String,
      default: '/mf-300h.png',
    },
    image_alt: {
      type: String,
      default: 'image',
    },
    onClick: {
      default: () => {},
    },
    button1: {
      type: String,
      default: 'Button',
    },
  },
}
</script>

<style scoped>
.mf-test-container {
  width: 100%;
  height: 400px;
  display: flex;
  position: relative;
  align-items: center;
  border-color: var(--dl-color-gray-black);
  border-width: 1px;
  flex-direction: column;
  justify-content: center;
  background-color: #e40f0f;
}
.mf-test-text {
  color: #2631a3;
  font-size: 30px;
  text-align: center;
}
.mf-test-image {
  width: 196px;
  height: 239px;
  object-fit: cover;
  border-color: #fb0202;
  border-width: 1px;
  margin-bottom: 0px;
}
.mf-test-button {
  margin-top: 10px;
  text-transform: capitalize;
}
@media(max-width: 1200px) {
  .mf-test-text {
    position: static;
  }
}
@media(max-width: 767px) {
  .mf-test-image {
    width: 268px;
  }
}
@media(max-width: 479px) {
  .mf-test-text {
    margin-bottom: 10px;
  }
  .mf-test-image {
    width: 252px;
  }
}
</style>
