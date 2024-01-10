<template>
  <div class="product12949-container">
    <div class="product12949-frame1427">
      <div class="product12949-frame1425">
        <div class="product12949-frame1421">
          <div class="product12949-frame1418">
            <span class="product12949-text">
              <span>Can&apos;t choose the right career path for you?</span>
            </span>
          </div>
        </div>
      </div>
      <div class="product12949-frame1426">
        <a
          :href="startFreeButtonProp"
          @click="this.$emit('onFreeClick')"
          class="product12949-buttons"
        >
          <span class="product12949-text2"><span>Start free test</span></span>
          <img
            alt="product12949-arrowrightup"
            src="/external/product12949-arrowrightup.svg"
            class="product12949-arrowrightup"
          />
        </a>
      </div>
      <div class="product12949-frame14271">
        <a
          :href="startPaidButtonProp"
          target="_blank"
          rel="noreferrer noopener"
          @click="this.$emit('onPaidClick')"
          class="product12949-buttons1"
        >
          <span class="product12949-text4"><span>Start paid test</span></span>
        </a>
      </div>
      <a :href="link_free" @click="this.$emit('onFreeLinkClick')">
        start free test link
      </a>
      <a :href="link_paid" @click="this.$emit('onPaidLinkClick')">
        start paid test link
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Product12949',
  props: {
    onPaidLinkClick: {
      default: () => {},
    },
    startPaidButtonProp: String,
    startFreeButtonProp: String,
    onFreeLinkClick: {
      default: () => {},
    },
    onPaidClick: {
      default: () => {},
    },
    link_paid: {
      type: String,
      default: 'https://example.com',
    },
    link_free: {
      type: String,
      default: 'https://example.com',
    },
    onFreeClick: {
      default: () => {},
    },
  },
}
</script>

<style scoped>
.product12949-container {
  width: 100%;
  height: auto;
  display: flex;
  position: relative;
  box-shadow: 0px 0px 2px 0px rgba(5, 20, 41, 0.05999999865889549) ;
  box-sizing: border-box;
  align-items: flex-start;
  flex-direction: column;
}
.product12949-frame1427 {
  gap: 16px;
  width: 100%;
  height: 273px;
  display: flex;
  padding: 16px;
  box-shadow: 0px 0px 2px 0px rgba(5, 20, 41, 0.05999999865889549) ;
  box-sizing: border-box;
  align-items: center;
  border-radius: 8px;
  flex-direction: column;
  background-color: rgba(255, 255, 255, 1);
}
.product12949-frame1425 {
  gap: 4px;
  width: 268px;
  display: flex;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.product12949-frame1421 {
  gap: 2px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.product12949-frame1418 {
  gap: 6px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.product12949-text {
  color: rgba(11, 13, 14, 1);
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
.product12949-frame1426 {
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
.product12949-buttons {
  gap: 4px;
  width: 265px;
  border: none;
  cursor: pointer;
  display: flex;
  padding: 8px 8px 8px 12px;
  background: none;
  align-items: center;
  flex-shrink: 0;
  border-radius: 4px;
  justify-content: center;
  text-decoration: none;
}
.product12949-text2 {
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
.product12949-arrowrightup {
  width: 24px;
  height: 24px;
}
.product12949-frame14271 {
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
  background-color: rgba(11, 113, 217, 1);
}
.product12949-buttons1 {
  gap: 4px;
  width: 266px;
  border: none;
  cursor: pointer;
  height: 40px;
  display: flex;
  padding: 8px 8px 8px 12px;
  background: none;
  align-items: center;
  flex-shrink: 0;
  border-radius: 4px;
  justify-content: center;
  text-decoration: none;
}
.product12949-text4 {
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
@media(max-width: 1200px) {
  .product12949-text {
    text-align: left;
  }
}
@media(max-width: 767px) {
  .product12949-container {
    width: 300px;
  }
}
@media(max-width: 479px) {
  .product12949-container {
    width: 300px;
  }
}
</style>
