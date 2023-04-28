<script>
import { store } from "../store";

export default {
  name: "AppMain",

  data() {
    return {
      store,
    };
  },
};
</script>

<template>
  <div class="wrapper" style="background-color: #edf2f5">
    <div class="container">
      <div class="container mt-5">
        <div class="row grid gap-3">
          <div class="col">
            <div class="card rounded-0" style="width: 18rem">
              <img
                src="../assets/img/photo-1496307042754-b4aa456c4a2d-370x200.jpeg"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body">
                <h5 class="card-title text-center">
                  How to be a DJ? Make Electronic Music
                </h5>
                <p class="card-text text-center" style="color: #b5b7c7">
                  Electronic
                </p>
                <p class="card-text">
                  <small class="text-body-secondary">
                    <i class="fa-solid fa-signal"></i> <span>Advanced</span>
                    <i class="fa-solid fa-list-ul"></i> <span>8 Lectures</span>
                    <i class="fa-regular fa-clock"></i> <span>6 hours</span>
                  </small>
                </p>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card rounded-0" style="width: 18rem">
              <img
                src="../assets/img/12345-1-370x200.png"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body">
                <h5 class="card-title text-center">
                  Nvidia and UE4 Technologies Practice
                </h5>
                <p class="card-text text-center" style="color: #b5b7c7">
                  Nvidia
                </p>
                <p class="card-text">
                  <small class="text-body-secondary">
                    <i class="fa-solid fa-signal"></i> <span>Advanced</span>
                    <i class="fa-solid fa-list-ul"></i> <span>8 Lectures</span>
                    <i class="fa-regular fa-clock"></i> <span>6 hours</span>
                  </small>
                </p>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card rounded-0" style="width: 18rem">
              <img
                src="../assets/img/photo-1491897554428-130a60dd4757-370x200.jpeg"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body">
                <h5 class="card-title text-center">
                  Fashion Photogrphy from professional
                </h5>
                <p class="card-text text-center" style="color: #b5b7c7">
                  Fashion
                </p>
                <p class="card-text">
                  <small class="text-body-secondary">
                    <i class="fa-solid fa-signal"></i> <span>Advanced</span>
                    <i class="fa-solid fa-list-ul"></i> <span>6 Lectures</span>
                    <i class="fa-regular fa-clock"></i> <span>6 hours</span>
                  </small>
                </p>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card rounded-0" style="width: 18rem">
              <img
                src="../assets/img/photo-1416339134316-0e91dc9ded92-370x200.jpeg"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body">
                <h5 class="card-title text-center">
                  Desing Instruments for Communication
                </h5>
                <p class="card-text text-center" style="color: #b5b7c7">
                  Communication
                </p>
                <p class="card-text">
                  <small class="text-body-secondary">
                    <i class="fa-solid fa-signal"></i>
                    <span>Intermediate</span>
                    <i class="fa-solid fa-list-ul"></i> <span>6 Lectures</span>
                    <i class="fa-regular fa-clock"></i> <span>6 hours</span>
                  </small>
                </p>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card rounded-0" style="width: 18rem">
              <img
                src="../assets/img/cathryn-lavery-67852-unsplash-370x200.jpg"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body">
                <h5 class="card-title text-center">
                  Make your Concept Right and Beautifulc
                </h5>
                <p class="card-text text-center" style="color: #b5b7c7">Art</p>
                <p class="card-text">
                  <small class="text-body-secondary">
                    <i class="fa-solid fa-signal"></i>
                    <span>Intermediate</span>
                    <i class="fa-solid fa-list-ul"></i> <span>6 Lectures</span>
                    <i class="fa-regular fa-clock"></i> <span>6 hours</span>
                  </small>
                </p>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card rounded-0" style="width: 18rem">
              <img
                src="../assets/img/photo-1475452779376-caebfb988090-370x200.jpeg"
                class="card-img-top"
                alt="..."
              />
              <div class="card-body">
                <h5 class="card-title text-center">
                  Road Bike Manual or How to Be a Champion.
                </h5>
                <p class="card-text text-center" style="color: #b5b7c7">
                  Bicycling
                </p>
                <p class="card-text">
                  <small class="text-body-secondary">
                    <i class="fa-solid fa-signal"></i> <span>Beginner</span>
                    <i class="fa-solid fa-list-ul"></i> <span>6 Lectures</span>
                    <i class="fa-regular fa-clock"></i> <span>6 hours</span>
                  </small>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="button-container">
      <button class="button">LOAD MORE</button>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  width: 80%;
}
.button-container {
  display: flex;
  justify-content: center;
  align-items: baseline;
}
.col {
  width: calc(33.33% - 10px);
}

i {
  padding-left: 0.5rem;
}
.button {
  margin: 3rem;
  border-radius: 30px;
  background-color: #ffc107;
  border-color: #ffc107;
  padding: 1rem;
  color: white;
}

.text-body-secondary i {
  color: #f2b91e;
}
</style>
