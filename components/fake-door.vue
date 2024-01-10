<template>
  <a :href="link_container" target="_blank" rel="noreferrer noopener">
    <div class="fake-door-container">
      <img :alt="image_alt" :src="image_src" class="fake-door-image" />
      <span>{{ text }}</span>
    </div>
  </a>
</template>

<script>
export default {
  name: 'FakeDoor',
  props: {
    text: {
      type: String,
      default: 'Text',
    },
    image_src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1687075379294-0a3189299656?ixid=M3w5MTMyMXwwfDF8YWxsfDN8fHx8fHwyfHwxNjg3MjQ5OTcxfA&ixlib=rb-4.0.3&w=300',
    },
    link_container: String,
    image_alt: {
      type: String,
      default: 'image',
    },
  },
}
</script>

<style scoped>
.fake-door-container {
  width: 944px;
  height: 400px;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
  text-decoration: none;
  background-color: var(--dl-color-primary-700);
}
.fake-door-image {
  width: 245px;
  height: 50%;
  object-fit: cover;
}
@media(max-width: 1200px) {
  .fake-door-container {
    width: 510px;
  }
}
</style>
