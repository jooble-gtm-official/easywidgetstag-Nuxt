<template>
  <div class="home-container"></div>
</template>

<script>
export default {
  name: 'Home',
  head: {
    title: 'easy_widget_stag',
    meta: [
      {
        property: 'og:title',
        content: 'easy_widget_stag',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  overflow: auto;
  box-shadow: 5px 5px 10px 0px #d4d4d4;
  min-height: 100vh;
  align-items: center;
  border-color: var(--dl-color-gray-black);
  border-width: 1px;
  flex-direction: column;
}
</style>
