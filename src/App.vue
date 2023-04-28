<script>
import AppHeaderTop from "./components/AppHeaderTop.vue";
import AppHeader from "./components/AppHeader.vue";
import AppTitle from "./components/AppTitle.vue";
import AppMain from "./components/AppMain.vue";
import { store } from "../src/store";
import AppOffer from "./components/AppOffer.vue";
import AppOpinions from "./components/AppOpinions.vue";
import AppNumbers from "./components/AppNumbers.vue";
import AppStudents from "./components/AppStudents.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  components: {
    AppHeaderTop,
    AppHeader,
    AppTitle,
    AppMain,
    AppOffer,
    AppOpinions,
    AppNumbers,
    AppStudents,
    AppFooter,
  },
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
    <AppHeaderTop />
    <AppHeader />
    <AppTitle :titleText="firstTitle" />
    <AppMain />

    <AppOffer />
    <AppTitle :titleText="secondTitle" />

    <AppOpinions />
    <AppNumbers />
    <AppTitle :titleText="thirdTitle" />
    <AppStudents />
    <AppFooter />
  </div>
</template>

<style lang="scss">
@use "./style/generals.scss";
</style>
