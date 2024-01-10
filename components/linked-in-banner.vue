<template>
  <div class="linked-in-banner-container">
    <a
      :href="LinkedInBanner"
      target="_blank"
      rel="noreferrer noopener"
      class="linked-in-banner-link"
    >
      <div
        @click="this.$emit('LinkedInBanner_Click')"
        class="linked-in-banner-frame206868"
      >
        <div class="linked-in-banner-frame206818">
          <div class="linked-in-banner-frame206817">
            <div class="linked-in-banner-frame206816">
              <span class="linked-in-banner-text">
                <span>Elevate your LinkedIn profile</span>
              </span>
              <span class="linked-in-banner-text2">
                <span>
                  Boost your opportunities by unlocking the power of LinkedIn.
                  Improve your profile using our suggestions to get noticed
                </span>
              </span>
            </div>
            <button
              @click="this.$emit('LinkedInBtn_Click')"
              class="linked-in-banner-buttons"
            >
              <span class="linked-in-banner-text4">
                <span>Start now (for free)</span>
              </span>
            </button>
          </div>
          <div class="linked-in-banner-frame206869">
            <img
              :alt="LinkedInFakeDoorImg_alt"
              :src="LinkedInFakeDoorImg_src"
              class="linked-in-banner-linked-in-fake-door-img"
            />
          </div>
        </div>
      </div>
    </a>
  </div>
</template>

<script>
export default {
  name: 'LinkedInBanner',
  props: {
    LinkedInFakeDoorImg_alt: {
      type: String,
      default: 'LinkedIn',
    },
    LinkedInFakeDoorImg_src: {
      type: String,
      default: '/external/linkedinfakedoorimg9195-uen-300w.png',
    },
    LinkedInBanner_Click: {
      default: () => {},
    },
    LinkedInBanner: String,
    LinkedInBtn: String,
    LinkedInBtn_Click: {
      default: () => {},
    },
  },
}
</script>

<style scoped>
.linked-in-banner-container {
  width: 796px;
  height: 248px;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.linked-in-banner-link {
  display: contents;
}
.linked-in-banner-frame206868 {
  gap: 10px;
  width: 796px;
  cursor: default;
  height: 248px;
  display: flex;
  position: relative;
  box-sizing: border-box;
  align-items: flex-start;
  border-radius: 8px;
  background-color: rgba(255, 255, 255, 1);
}
.linked-in-banner-frame206818 {
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
.linked-in-banner-frame206817 {
  gap: 20px;
  top: 0px;
  left: 0px;
  width: 492px;
  height: 200px;
  display: flex;
  position: absolute;
  align-items: flex-start;
}
.linked-in-banner-frame206816 {
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
.linked-in-banner-text {
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
.linked-in-banner-text2 {
  top: 48px;
  color: rgba(56, 62, 71, 1);
  width: 492px;
  height: auto;
  position: absolute;
  font-size: 18px;
  align-self: stretch;
  font-style: Regular;
  text-align: left;
  font-family: Inter;
  font-weight: 400;
  line-height: 28px;
  font-stretch: normal;
  text-decoration: none;
}
.linked-in-banner-buttons {
  gap: 10px;
  top: 152px;
  left: 0px;
  width: 179px;
  cursor: pointer;
  display: flex;
  padding: 12px 16px;
  position: absolute;
  align-items: center;
  border-radius: 4px;
  justify-content: center;
  text-decoration: none;
  background-color: rgba(11, 113, 217, 1);
}
.linked-in-banner-text4 {
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
.linked-in-banner-frame206869 {
  gap: 10.243903160095215px;
  top: 0px;
  left: 506px;
  width: 242px;
  height: 191px;
  display: flex;
  overflow: hidden;
  position: absolute;
  align-items: flex-start;
  background-color: rgba(255, 255, 255, 1);
}
.linked-in-banner-linked-in-fake-door-img {
  width: 243px;
  height: 191px;
}
</style>
