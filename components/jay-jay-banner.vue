<template>
  <div class="jay-jay-banner-container">
    <a
      href="https://jayjay.co/cara-terbaik-memulai-karir-sukses-di-bidang-it-dari-awal?utm_source=jooble&amp;utm_medium=website&amp;utm_campaign=webinar_qa"
      target="_blank"
      rel="noreferrer noopener"
      class="jay-jay-banner-link"
    >
      <div
        @click="this.$emit('onClick')"
        class="jay-jay-banner-container1 container1"
      >
        <img
          alt="image"
          src="/external/jay_jay_banner_1024-200h-200h.png"
          class="jay-jay-banner-image1240 image_10241"
        />
        <img
          alt="image"
          src="/external/jay_jay_banner_320-200h-200h.png"
          class="jay-jay-banner-image320 image_3201"
        />
        <img
          alt="image"
          src="/external/jay_jay_banner_768-200h-200h.png"
          class="jay-jay-banner-image768 image_7681"
        />
      </div>
    </a>
  </div>
</template>

<script>
export default {
  name: 'JayJayBanner',
  props: {
    text: {
      type: String,
      default: 'Text',
    },
    onClick: {
      default: () => {},
    },
  },
}
</script>

<style scoped>
.jay-jay-banner-container {
  width: 100%;
  height: auto;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.jay-jay-banner-link {
  display: contents;
}
.jay-jay-banner-container1 {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  background: linear-gradient(     90deg,     #b2e4ff 0%,     #b5ddff 26%,     #bdcbff 58%,     #caadff 79%,     #d593ff 100%   );
  align-items: center;
  border-color: #f30808;
  border-width: 5px;
  justify-content: center;
  text-decoration: none;
}
.jay-jay-banner-image1240 {
  width: 1024px;
  height: auto;
  display: block;
  min-width: 1024px;
  border-color: var(--dl-color-gray-black);
  border-style: dashed;
  border-width: 1px;
}
.jay-jay-banner-image320 {
  width: 320px;
  height: auto;
  display: none;
  min-width: 320px;
}
.jay-jay-banner-image768 {
  width: 768px;
  height: auto;
  display: none;
  min-width: 768px;
}
@media(max-width: 1400px) {
  .jay-jay-banner-image320 {
    display: none;
  }
  .jay-jay-banner-image768 {
    display: none;
  }
}
@media(max-width: 992px) {
  .jay-jay-banner-image1240 {
    display: none;
  }
  .jay-jay-banner-image320 {
    display: none;
  }
  .jay-jay-banner-image768 {
    display: flex;
  }
}
@media(max-width: 768px) {
  .jay-jay-banner-image320 {
    display: flex;
  }
  .jay-jay-banner-image768 {
    display: none;
  }
}
@media(max-width: 480px) {
  .jay-jay-banner-container1 {
    width: 100%;
    justify-content: center;
  }
  .jay-jay-banner-image320 {
    display: flex;
  }
}
</style>
