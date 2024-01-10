<template>
  <div class="component-for-testing-props-container">
    <span class="component-for-testing-props-title">
      {{ Component_for_testing_title }}
    </span>
    <span class="component-for-testing-props-subtitle">
      {{ component_for_testing_subtitle }}
    </span>
  </div>
</template>

<script>
export default {
  name: 'ComponentForTestingProps',
  props: {
    component_for_testing_subtitle: {
      type: String,
      default: 'We work on 68 countries',
    },
    Component_for_testing_title: {
      type: String,
      default: 'title',
    },
  },
}
</script>

<style scoped>
.component-for-testing-props-container {
  width: 100%;
  height: 200px;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
  background-color: var(--dl-color-primary-700);
}
.component-for-testing-props-title {
  align-self: center;
  font-style: normal;
  font-weight: 900;
}
.component-for-testing-props-subtitle {
  align-self: center;
  font-style: normal;
  margin-top: 25px;
  font-weight: 600;
  text-transform: capitalize;
}
</style>
