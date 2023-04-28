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
  <section class="jumbotron">
    <div
      class="card text-start bg-transparent border border-0"
      style="width: 40rem"
    >
      <div class="card-body">
        <h1>
          Start your Human
          <span style="color: #f2b91e">Revolution</span> today
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
          <h5 class="sale">
            <span style="color: white">Limited sale:</span> All courses with 55%
            off
          </h5>
          <div class="custom-search">
            <input
              type="text"
              class="custom-search-input"
              placeholder="Enter your email"
            />
            <button class="custom-search-botton" type="submit">
              SUBSCRIBE
            </button>
          </div>
        </div>
        <div class="col mt-4">
          <div class="row numbers">
            <div class="col">
              <span>26</span>
            </div>
            <div class="col">
              <span>01</span>
            </div>
            <div class="col">
              <span>47</span>
            </div>
            <div class="col">
              <span>35</span>
            </div>
          </div>
          <div class="row description">
            <div class="col">
              <span>Days</span>
            </div>
            <div class="col">
              <span>Hours</span>
            </div>
            <div class="col">
              <span>Minutes</span>
            </div>
            <div class="col">
              <span>Seconds</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="description">
    <div class="container">
      <div class="row">
        <div class="col descr">
          <h2 style="font-weight: bold">
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

.jumbotron {
  height: 800px;
  background-image: url("../assets/img/slide-1.jpg");
  background-size: cover;
  position: relative;

  .card {
    position: absolute;
    left: 800px;
    top: 200px;
  }

  h1 {
    font-size: 4rem;
    font-weight: bold;
  }
}

.yellow-countdown {
  position: absolute;
  top: 50rem;
  right: 19rem;
  height: 200px;
  width: 70%;
  background-color: #f2b91e;
  border-radius: 5px;
  margin: 0 auto;

  h5 {
    font-weight: bold;
    font-size: 1.5rem;
  }
}
.description {
  margin-top: 10rem;
}

.descr {
  display: flex;
  flex-direction: column;

  img {
    margin-top: 1rem;
  }
}

.numbers {
  color: white;
  font-size: 4rem;
  font-weight: bolder;
}

.custom-search {
  position: relative;
  width: 400px;
}
.custom-search-input {
  width: 100%;
  border: 0.2px solid white;
  border-radius: 100px;
  padding: 10px 100px 10px 20px;
  box-sizing: border-box;
  outline: none;
}
.custom-search-botton {
  position: absolute;
  right: 3px;
  top: 3px;
  bottom: 3px;
  border: 0;
  background: #2d4649;
  color: #fff;
  outline: none;
  border-radius: 100px;
  z-index: 2;
}
</style>
