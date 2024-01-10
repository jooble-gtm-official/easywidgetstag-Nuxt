<template>
  <div class="tailoring-banner-container">
    <div class="tailoring-banner-frame206864">
      <div class="tailoring-banner-frame206818">
        <div class="tailoring-banner-frame206817">
          <div class="tailoring-banner-frame206816">
            <span class="tailoring-banner-text">
              <span>Instant resume tailoring</span>
            </span>
            <span class="tailoring-banner-text2 ParagraphP18">
              <span>
                <span>
                  70% of resumes never get proper attention because of low
                  relevance. Leverage AI power today to create a
                </span>
                <br />
                <span>hireable one</span>
              </span>
            </span>
          </div>
          <a
            :href="TailoringBtn"
            target="_blank"
            rel="noreferrer noopener"
            @click="this.$emit('TailoringBtn_Click')"
            class="tailoring-banner-buttons"
          >
            <span class="tailoring-banner-text7"><span>Tailor now</span></span>
          </a>
        </div>
        <div class="tailoring-banner-tailoringimg">
          <img
            :alt="Tailoringimg_alt"
            :src="Tailoringimg_src"
            class="tailoring-banner-tailoringimg1"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TailoringBanner',
  props: {
    TailoringImg_alt: {
      type: String,
      default: 'Frame20689119194',
    },
    TailoringBtn: String,
    Tailoring_img: {
      type: String,
      default:
        'https://aheioqhobo.cloudimg.io/v7/_playground-bucket-v2.teleporthq.io_/2efd2abf-277a-4be3-99bc-38d3555327ef/e765225f-681a-473f-8e68-4f17c19b1cdd?org_if_sml=1125434',
    },
    Tailoringimg_alt: {
      type: String,
      default: 'Tailoringimg9194',
    },
    TailoringBtn_Click: {
      default: () => {},
    },
    Tailoringimg_src: {
      type: String,
      default: '/external/tailoringimg9194-6wz-300w.png',
    },
  },
}
</script>

<style scoped>
.tailoring-banner-container {
  width: 796px;
  height: 248px;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.tailoring-banner-frame206864 {
  gap: 10px;
  width: 100%;
  height: 248px;
  display: flex;
  position: relative;
  align-items: flex-start;
  border-radius: 8px;
  background-color: rgba(255, 255, 255, 1);
}
.tailoring-banner-frame206818 {
  gap: 38px;
  top: 24px;
  left: 24px;
  width: 748px;
  height: 200px;
  display: flex;
  position: absolute;
  align-items: flex-start;
  flex-shrink: 0;
  justify-content: space-between;
}
.tailoring-banner-frame206817 {
  gap: 20px;
  top: 0px;
  left: 0px;
  width: 492px;
  height: 200px;
  display: flex;
  position: absolute;
  align-items: flex-start;
}
.tailoring-banner-frame206816 {
  gap: 8px;
  top: 0px;
  left: 0px;
  width: 492px;
  height: 132px;
  display: flex;
  position: absolute;
  align-items: flex-start;
  flex-shrink: 0;
}
.tailoring-banner-text {
  color: rgba(56, 62, 71, 1);
  width: 492px;
  height: auto;
  position: absolute;
  font-size: 28px;
  align-self: stretch;
  font-style: Bold;
  text-align: left;
  font-family: Inter;
  font-weight: 700;
  line-height: 40px;
  font-stretch: normal;
  text-decoration: none;
}
.tailoring-banner-text2 {
  top: 48px;
  color: rgba(56, 62, 71, 1);
  width: 492px;
  height: auto;
  position: absolute;
  align-self: stretch;
  text-align: left;
  line-height: 28px;
}
.tailoring-banner-buttons {
  gap: 10px;
  top: 152px;
  left: 0px;
  width: 111px;
  display: flex;
  padding: 12px 16px;
  position: absolute;
  align-items: center;
  border-radius: 4px;
  justify-content: center;
  text-decoration: none;
  background-color: rgba(11, 113, 217, 1);
}
.tailoring-banner-text7 {
  color: rgba(255, 255, 255, 1);
  height: auto;
  font-size: 16px;
  font-style: Medium;
  text-align: center;
  font-family: Inter;
  font-weight: 500;
  line-height: 24px;
  font-stretch: normal;
  text-decoration: none;
}
.tailoring-banner-tailoringimg {
  top: 0px;
  left: 506px;
  width: 242px;
  height: 191px;
  display: flex;
  overflow: hidden;
  position: absolute;
  align-items: flex-start;
  flex-shrink: 0;
}
.tailoring-banner-tailoringimg1 {
  width: 242px;
  height: 191px;
}
@media(max-width: 479px) {
  .tailoring-banner-frame206864 {
    align-self: flex-start;
  }
}
</style>
