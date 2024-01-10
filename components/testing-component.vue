<template>
  <div class="testing-component-container">
    <div class="testing-component-frame1427">
      <img :alt="img51_alt1" :src="img51_src1" class="testing-component-img51" />
      <div class="testing-component-frame1425">
        <div class="testing-component-frame1421">
          <div class="testing-component-frame1418">
            <span class="testing-component-text">{{ text }}</span>
            <span class="testing-component-text1">
              <span>
                Take a quick free test to discover your ideal career and receive a
                personalized Job Report
              </span>
            </span>
          </div>
        </div>
      </div>
      <div class="testing-component-frame1426">
        <button class="testing-component-buttons">
          <span class="testing-component-text3">
            <span>Start free test</span>
          </span>
          <img
            alt="arrowrightup054"
            src="/external/arrowrightup054-u3gc.svg"
            class="testing-component-arrowrightup"
          />
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TestingComponent',
  props: {
    text: {
      type: String,
      default: "Can't choose the right career path for you?",
    },
    img51_alt1: {
      type: String,
      default: 'img51155',
    },
    img51_src: {
      type: String,
      default:
        'https://aheioqhobo.cloudimg.io/v7/_playground-bucket-v2.teleporthq.io_/2efd2abf-277a-4be3-99bc-38d3555327ef/04c327ff-58ca-474f-85d3-023dfeb602d0?org_if_sml=1628516',
    },
    img51_src1: {
      type: String,
      default: '/external/testing_component_image-200h.png',
    },
    img51_alt: {
      type: String,
      default: 'img51155',
    },
  },
}
</script>

<style scoped>
.testing-component-container {
  width: 344px;
  height: 359px;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.testing-component-frame1427 {
  gap: 16px;
  width: 100%;
  height: 377px;
  display: flex;
  padding: 16px;
  box-shadow: 0px 0px 2px 0px rgba(5, 20, 41, 0.05999999865889549) ;
  align-items: flex-start;
  border-radius: 8px;
  flex-direction: column;
  background-color: rgba(255, 255, 255, 1);
}
.testing-component-img51 {
  width: 259px;
  height: 135px;
}
.testing-component-frame1425 {
  gap: 4px;
  width: 268px;
  display: flex;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.testing-component-frame1421 {
  gap: 2px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.testing-component-frame1418 {
  gap: 6px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.testing-component-text {
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
  text-decoration: none;
}
.testing-component-text1 {
  color: rgba(57, 63, 71, 1);
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
.testing-component-frame1426 {
  gap: 10px;
  width: 267px;
  cursor: pointer;
  display: flex;
  align-items: flex-start;
  flex-shrink: 0;
  border-color: rgba(11, 113, 217, 1);
  border-style: solid;
  border-width: 1px;
  border-radius: 4px;
  justify-content: center;
}
.testing-component-buttons {
  gap: 4px;
  display: flex;
  padding: 8px 8px 8px 12px;
  align-items: center;
  border-radius: 4px;
  justify-content: center;
}
.testing-component-text3 {
  color: rgba(11, 113, 217, 1);
  width: 100%;
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
.testing-component-arrowrightup {
  width: 24px;
  height: 24px;
}
</style>
