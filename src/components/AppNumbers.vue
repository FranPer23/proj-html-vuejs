<script>
import { store } from "../store";

export default {
  name: "AppNumbers",
  data() {
    return {
      store,
    };
  },
};
</script>

<template>
  <div class="numbers-background flex">
    <div class="counter-container flex">
      <div class="left">
        <i class="fa-solid fa-user-group fa-2xl"></i>
      </div>
      <div class="right">
        <h2>3195</h2>
        <p>Online Learner</p>
      </div>
      <div class="left">
        <i class="fa-solid fa-film fa-2xl"></i>
      </div>
      <div class="right">
        <h2>23</h2>
        <p>Video Courses</p>
      </div>
      <div class="left">
        <i class="fa-solid fa-images fa-2xl"></i>
      </div>
      <div class="right">
        <h2>437</h2>
        <p>Sliders & Images</p>
      </div>
      <div class="left">
        <i class="fa-regular fa-thumbs-up fa-2xl"></i>
      </div>
      <div class="right">
        <h2>1440</h2>
        <p>Excellent Reviews</p>
      </div>
      <div class="left"></div>
      <div class="right">
        <h2></h2>
        <p></p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.numbers-background {
  margin-top: 3rem;
  height: 500px;
  background-image: url("../assets/img/counter-1919x1101.jpg");
  color: white;
}

h2 {
  color: #f2b91e;
}

.counter-container {
  width: 70%;
  margin: 0 auto;
  height: 100px;
}
.flex {
  display: flex;
  align-items: center;
  justify-content: center;
  justify-content: space-evenly;
}

.left {
  padding-left: 5rem;
}

.right {
  line-height: 0rem;
  padding-left: 0.5rem;
}
</style>
