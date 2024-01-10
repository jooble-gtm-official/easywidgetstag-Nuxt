<template>
  <div class="new-widget1-container">
    <div class="new-widget1-frame1427">
      <div class="new-widget1-frame1425">
        <div class="new-widget1-img">
          <img :alt="img41_alt" :src="img41_src" class="new-widget1-img41" />
        </div>
        <div class="new-widget1-frame1421">
          <div class="new-widget1-frame1418">
            <span class="new-widget1-text">
              Can&apos;t choose the right career path for you?
            </span>
            <span class="new-widget1-text1">
              <span class="new-widget1-text2">
                Take
                <span v-html="raw78to"></span>
              </span>
              <span>
                a quick free test to discover your ideal career and receive a
                personalized Job Report
              </span>
            </span>
          </div>
        </div>
      </div>
      <div class="new-widget1-frame1426">
        <button class="new-widget1-buttons">
          <span class="new-widget1-text4"><span>Start free test</span></span>
          <img
            alt="arrowrightup054"
            src="/external/arrowrightup054-3f3e.svg"
            class="new-widget1-arrowrightup"
          />
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NewWidget1',
  props: {
    img41_alt: {
      type: String,
      default: 'img41432',
    },
    desc: {
      type: String,
      default: 'Description',
    },
    text11: {
      type: String,
      default: "Can't choose the right career path for you?",
    },
    img41_src: {
      type: String,
      default: '/external/img41432-1f0g-200h.png',
    },
  },
  data() {
    return {
      raw78to: ' ',
    }
  },
}
</script>

<style scoped>
.new-widget1-container {
  width: 298px;
  height: 360px;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.new-widget1-frame1427 {
  gap: 16px;
  width: 298px;
  height: auto;
  display: flex;
  padding: 16px;
  box-shadow: 0px 0px 2px 0px rgba(5, 20, 41, 0.05999999865889549) ;
  align-items: flex-start;
  border-radius: 8px;
  flex-direction: column;
  background-color: rgba(255, 255, 255, 1);
}
.new-widget1-frame1425 {
  gap: 4px;
  width: 268px;
  display: flex;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.new-widget1-img {
  width: 268px;
  height: 135px;
  display: flex;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  border-radius: 6px;
  justify-content: center;
}
.new-widget1-img41 {
  width: 255px;
  height: 163px;
}
.new-widget1-frame1421 {
  gap: 2px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.new-widget1-frame1418 {
  gap: 6px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.new-widget1-text {
  color: rgb(11, 13, 14);
  height: auto;
  font-size: 18px;
  align-self: stretch;
  font-style: Bold;
  text-align: left;
  font-family: Inter;
  font-weight: 700;
  line-height: 28px;
  font-stretch: normal;
  text-transform: capitalize;
  text-decoration: none;
}
.new-widget1-text1 {
  color: rgb(57, 63, 71);
  height: auto;
  font-size: 16px;
  align-self: stretch;
  font-style: Regular;
  text-align: left;
  font-family: Inter;
  font-weight: 400;
  line-height: 24px;
  font-stretch: normal;
  text-decoration: none;
}
.new-widget1-text2 {
  text-transform: capitalize;
}
.new-widget1-frame1426 {
  gap: 10px;
  width: 267px;
  display: flex;
  align-items: flex-start;
  flex-shrink: 0;
  border-color: rgba(11, 113, 217, 1);
  border-style: solid;
  border-width: 1px;
  border-radius: 4px;
  justify-content: center;
}
.new-widget1-buttons {
  gap: 4px;
  display: flex;
  padding: 8px 8px 8px 12px;
  align-items: center;
  border-radius: 4px;
  justify-content: center;
}
.new-widget1-text4 {
  color: rgba(11, 113, 217, 1);
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
.new-widget1-arrowrightup {
  width: 24px;
  height: 24px;
}
</style>
