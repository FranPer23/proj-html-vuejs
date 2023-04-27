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
    <div
      class="card text-start bg-transparent border border-0"
      style="width: 30rem"
    >
      <div class="card-body">
        <h1 class="fs-1">
          Start your Human
          <span>Revolution</span> today
        </h1>
        <p class="card-text">
          A wonderful serenity has taken possession of my entire soul, like
          these sweet mornings of spring which I enjoy with my whole heart
        </p>
      </div>
    </div>
  </section>
  <section class="countdown">
    <div class="yellow-countdown text-center">
      <div class="row">
        <div class="col mt-5">
          <h5>Limited sale: All course with 55% off</h5>
          <input type="text" />
          <button>Subscribe</button>
        </div>
        <div class="col mt-5">
          <p>countdown</p>
        </div>
      </div>
    </div>
  </section>

  <section class="description">
    <div class="container text-center">
      <div class="row">
        <div class="col">
          <h2>
            Hey there, my name is John Doe. I'm the founder of the Brain
            Academy.
          </h2>
          <img src="../assets/img/sign.jpg" alt="" />
        </div>
        <div class="col">
          <div class="text-start">
            <div class="card-body">
              <p class="card-text">
                A wonderful serenity has taken possession of my entire soul,
                like these sweet mornings of spring which I enjoy with my whole
                heart. I am alone, and feel the charm of existence in this spot,
                which was created for the bliss of souls like mine. I am so
                happy, my dear friend, so absorbed in the exquisite sense of
                mere tranquil existence, that I neglect my talents. I should be
                incapable of drawing a single stroke at the present moment; and
                yet I feel that I never was a greater artist than now. When,
                while the lovely valley teems with vapour around me, and the
                meridian sun strikes the upper surface of the impenetrable
                foliage of my trees, and but a few stray gleams steal into the
                inner sanctuary
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
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
  position: relative;

  span {
    color: #f2b91e;
  }
  .card {
    position: absolute;
    left: 700px;
    top: 200px;
  }
}

.yellow-countdown {
  height: 200px;
  width: 70%;
  background-color: #f2b91e;
  border-radius: 5px;
  margin: 0 auto;
}
</style>
