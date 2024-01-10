<template>
  <div class="testwidget-container">
    <div class="testwidget-frame1427">
      <div class="testwidget-frame14271">
        <div class="testwidget-frame1425">
          <div class="testwidget-img">
            <img :alt="img41_alt1" :src="img41_src1" class="testwidget-img41" />
          </div>
          <div class="testwidget-frame1421">
            <div class="testwidget-frame1418">
              <span class="testwidget-text">
                Can&apos;t choose the right career path for you?
              </span>
              <span class="testwidget-text1">
                Take a quick free test to discover your ideal career and receive a
                personalized Job Report
              </span>
            </div>
          </div>
        </div>
        <div class="testwidget-frame1426">
          <button class="testwidget-buttons">
            <span class="testwidget-text2">{{ text }}</span>
            <img
              alt="arrowrightup054"
              src="/external/arrowrightup054-3f3e.svg"
              class="testwidget-arrowrightup"
            />
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Testwidget',
  props: {
    FreeTest: String,
    img41_src1: {
      type: String,
      default: '/external/img41432-1f0g-200h.png',
    },
    img41_alt: {
      type: String,
      default: 'img41432',
    },
    img41_alt1: {
      type: String,
      default: 'img41432',
    },
    img41_src: {
      type: String,
      default:
        'https://aheioqhobo.cloudimg.io/v7/_playground-bucket-v2.teleporthq.io_/2efd2abf-277a-4be3-99bc-38d3555327ef/66575a23-5148-4a51-8a90-a4243b020dc1?org_if_sml=1626956',
    },
    text: {
      type: String,
      default: 'Start free test',
    },
    Free_TestClick: {
      default: () => {},
    },
    Free_Test: String,
    btn: {
      type: String,
      default: 'Save',
    },
  },
}
</script>

<style scoped>
.testwidget-container {
  width: 285px;
  height: 358px;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.testwidget-frame1427 {
  gap: 16px;
  width: 338px;
  height: 398px;
  display: flex;
  padding: 16px;
  box-shadow: 0px 0px 2px 0px rgba(5, 20, 41, 0.05999999865889549) ;
  align-items: flex-start;
  border-radius: 8px;
  flex-direction: column;
  background-color: rgba(255, 255, 255, 1);
}
.testwidget-frame14271 {
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
.testwidget-frame1425 {
  gap: 4px;
  width: 268px;
  display: flex;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.testwidget-img {
  width: 268px;
  height: 135px;
  display: flex;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  border-radius: 6px;
  justify-content: center;
}
.testwidget-img41 {
  width: 255px;
  height: 163px;
}
.testwidget-frame1421 {
  gap: 2px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.testwidget-frame1418 {
  gap: 6px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.testwidget-text {
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
.testwidget-text1 {
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
.testwidget-frame1426 {
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
.testwidget-buttons {
  gap: 4px;
  display: flex;
  padding: 8px 8px 8px 12px;
  align-items: center;
  border-radius: 4px;
  justify-content: center;
}
.testwidget-text2 {
  color: rgb(11, 113, 217);
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
.testwidget-arrowrightup {
  width: 24px;
  height: 24px;
}
</style>
