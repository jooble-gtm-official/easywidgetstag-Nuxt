<template>
  <div class="localization-container">
    <span class="localization-title">{{ localizationTitle }}</span>
    <span class="localization-subtitle">{{ localizationSubtitle }}</span>
    <span class="localization-description">{{ localizationDescription }}</span>
  </div>
</template>

<script>
export default {
  name: 'Localization',
  props: {
    localizationTitle: {
      type: String,
      default: 'title',
    },
    localizationDescription: {
      type: String,
      default: 'Description',
    },
    localizationSubtitle: {
      type: String,
      default: 'subtitle',
    },
  },
}
</script>

<style scoped>
.localization-container {
  width: 100%;
  height: 400px;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
  background-color: var(--dl-color-primary-500);
}
.localization-title {
  font-size: 40px;
  font-style: normal;
  font-weight: 900;
}
.localization-subtitle {
  font-size: 40px;
  font-style: normal;
  font-weight: 900;
}
.localization-description {
  font-size: 60px;
}
</style>
