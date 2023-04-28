<script>
export default {
  name: "AppStudents",
};
</script>

<template>
  <div class="container">
    <div class="carousel">
      <div class="pictures mt">
        <i class="fa-solid fa-arrow-left fa-2xl"></i>
        <img src="../assets/img/1-100x100.jpg" alt="" />
        <img style="width: 8rem" src="../assets/img/2-100x100.jpg" alt="" />
        <img src="../assets/img/4-100x100.jpg" alt="" />
        <i class="fa-solid fa-arrow-right fa-2xl"></i>
      </div>
      <div class="comment text-center mt-5 mb-5">
        <h3>Paints of the Future</h3>
        <span v-for="i in 5" :key="i" style="color: #f2b91e"
          ><i class="fa-solid fa-star"></i
        ></span>
        <p class="mt-3" style="width: 40rem">
          "The response to your MasterStudy has been really overwhelming! Those
          who participated in the workshop are spreading the word here on campus
          and the "buzz" is on. The VP of Instruction wants you to come back!
          Her goal is to have more faculty trained. She also wants to attend a
          workshop herself. Our President told me Masterstudy needs to be the
          cornerstone of our success program."
        </p>
      </div>
    </div>
    <div class="carousel-text"></div>
  </div>
</template>

<style lang="scss">
@use "../style/generals.scss";

.pictures {
  width: 40%;
  display: flex;
  justify-content: center;
  align-items: center;

  img {
    border-radius: 50%;
  }
}
</style>
