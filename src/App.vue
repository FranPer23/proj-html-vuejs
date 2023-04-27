<script>
import AppHeader from "./components/AppHeader.vue";
import AppTitle from "./components/AppTitle.vue";
import AppMain from "./components/AppMain.vue";
import { store } from "../src/store";

export default {
  components: { AppHeader, AppTitle, AppMain },
  data() {
    return {
      store,
      firstTitle: "New Courses",
      secondTitle: "Why my courses?",
      thirdTitle: "What students say?",
    };
  },
};
</script>

<template>
  <div>
    <AppHeader />
    <AppTitle :titleText="firstTitle" />
    <AppMain />
    <AppTitle :titleText="secondTitle" />
    <AppTitle :titleText="thirdTitle" />
  </div>
</template>

<style lang="scss" scoped></style>
