<script>
import { store } from "../store";

export default {
  name: "AppHeader",
  data() {
    return {
      store,
    };
  },
};
</script>

<template>
  <header class="header">
    <div class="head-container flex">
      <div class="head-item">
        <img class="logo" src="../assets/img/MasterStudy-1.svg" alt="" />
      </div>
      <div class="head-item">
        <a href="">Courses</a>
        <a href="">Course Formats</a>
        <a href="">Add Course</a>
        <a href="">Pages</a>
        <a href="">Demos</a>
      </div>
      <div class="icons head-item">
        <i class="fa-brands fa-linkedin"></i>
        <i class="fa-brands fa-instagram"></i>
        <i class="fa-brands fa-facebook"></i>
        <i class="fa-brands fa-twitter"></i>
      </div>
    </div>
  </header>
  <section class="jumbotron">
    <div class="title-container">
      <div class="title">
        <h1>
          Start your Human <br />
          <span>Revolution</span> today
        </h1>
        <p>
          A wonderful serenity has taken possession of my entire soul, like
          <br />
          these sweet mornings of spring which I enjoy with my whole heart
        </p>
      </div>
    </div>
  </section>
  <div class="countdown">
    <div class="countdown-content">
      <span>Limited sale: All courses with 55% off</span>
      <input type="text" />
      <button>Subscribe</button>
      <div>1234567890</div>
    </div>
  </div>
</template>

<style lang="scss">
@use "../style/generals.scss";
.header {
  height: 100px;
}

.flex {
  display: flex;
  align-items: center;
  justify-content: center;
  padding-top: 1.5rem;
}
.logo {
  margin-right: 14rem;
}

.head-item {
  margin-left: 1rem;
}

a {
  text-decoration: none;
  padding-left: 1rem;
  color: black;
}

i {
  padding-left: 1rem;
}

.jumbotron {
  height: 800px;
  background-image: url("../assets/img/slide-1.jpg");
  background-size: cover;

  .title-container {
    position: relative;
  }

  .title h1 {
    font-size: 4.5rem;
  }

  .title {
    font-weight: 400;
    position: absolute;
    left: 800px;
    top: 180px;
  }

  span {
    color: #f2b91e;
  }
}

.countdown {
  height: 100px;
  width: 600px;
  background-color: #f2b91e;
  border-radius: 5px;
}
</style>
