<script>
export default {
  name: "AppTitle",
  props: {
    titleText: String,
  },
};
</script>

<template>
  <div>
    <h2>{{ titleText }}</h2>
  </div>
</template>

<style lang="scss" scoped>
h2 {
  text-align: center;
  color: blue;
}
</style>
