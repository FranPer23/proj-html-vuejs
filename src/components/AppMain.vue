<script>
import { store } from "../store";

export default {
  name: "AppMain",
  props: {
    title: String,
    text: String,
    infos: String,
  },
  data() {
    return {
      store,
    };
  },
  computed: {
    getImg(imgPath) {},
  },
};
</script>

<template>
  <div class="container">
    <div class="row">
      <div class="col">
        <div class="card text-center" style="width: 30rem">
          <div class="card-body">
            <img src="" class="card-img-top" alt="..." />
            <h5 class="card-title">{{ title }}</h5>
            <p class="card-text">
              {{ text }}
            </p>
            <p class="card-text">
              {{ genre }}
            </p>
          </div>
          <div class="card-footer text-body-secondary">
            <i class="fa-solid fa-signal"></i> <span>{{ level }}</span>
            <i class="fa-solid fa-list-ul"></i>
            <span>{{ number }} Lectures</span>
            <i class="fa-regular fa-clock"></i> <span>{{ time }} hours</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
