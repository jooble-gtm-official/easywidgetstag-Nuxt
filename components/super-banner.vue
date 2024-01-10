<template>
  <a href="https://link" target="_blank" rel="noreferrer noopener">
    <div @click="this.$emit('onClick')" class="super-banner-container">
      <span class="super-banner-title">{{ superBannerTitle }}</span>
      <span class="super-banner-subtitle">{{ SuperBannerSubtitle }}</span>
      <span class="super-banner-description">{{ SuperBannerDescription }}</span>
      <span class="super-banner-region">{{ superBannerRegion }}</span>
    </div>
  </a>
</template>

<script>
export default {
  name: 'SuperBanner',
  props: {
    SuperBannerSubtitle: {
      type: String,
      default: 'Subtitle',
    },
    superBannerTitle: {
      type: String,
      default: 'Title',
    },
    onClick: {
      default: () => {},
    },
    SuperBannerDescription: {
      type: String,
      default: 'Description',
    },
    superBannerRegion: {
      type: String,
      default: 'region',
    },
  },
}
</script>

<style scoped>
.super-banner-container {
  color: rgb(70, 69, 140);
  width: 100%;
  border: 5px solid rgb(232, 169, 169);
  height: auto;
  display: flex;
  padding: 10px;
  position: relative;
  flex-wrap: wrap;
  box-sizing: border-box;
  align-items: center;
  flex-direction: column;
  text-decoration: none;
  background-color: rgb(244, 211, 211);
}
.super-banner-title {
  font-size: 25px;
  font-style: normal;
  font-weight: 500;
}
.super-banner-subtitle {
  font-size: 20px;
  font-style: normal;
  margin-top: 10px;
  font-weight: 500;
}
.super-banner-description {
  margin-top: 15px;
}
.super-banner-region {
  margin-top: 10px;
}
@media(max-width: 479px) {
  .super-banner-description {
    align-self: center;
  }
}
</style>
