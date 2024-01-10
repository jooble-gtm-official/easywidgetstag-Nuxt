<template>
  <div class="testdocumentation-container"><span>{{ text }}</span></div>
</template>

<script>
export default {
  name: 'Testdocumentation',
  props: {
    text: {
      type: String,
      default: 'Text',
    },
  },
}
</script>

<style scoped>
.testdocumentation-container {
  width: 100%;
  height: 400px;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
</style>
