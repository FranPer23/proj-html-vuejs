<script>
export default {
  name: "AppOffer",
};
</script>

<template>
  <div class="offer-container d-flex align-items-center justify-content-evenly">
    <div class="row">
      <div class="col-sm-7 p-3 text-center">
        <h1>Get My Exclusive Investing Book just for $19.50</h1>
        <p>
          Vestibulum imentum en urna vel cursus. Aenean vehicula quam quam,
          vitae pellentesque urna elementum cursus.
        </p>
        <img class="amazon" src="../assets/img/amazon.png" alt="" />
      </div>
      <div class="col-3 p-3 mb-2">
        <img class="book" src="../assets/img/book.png" alt="" />
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.offer-container {
  width: 100%;
  height: 500px;
  background-image: url(../assets/img/slider_1-1917x607-1914x606.jpg);
  position: relative;

  h1 {
    color: #ffc107;
  }
  p {
    color: white;
    font-style: italic;
  }
}

.book {
  height: 80%;
  position: absolute;
  bottom: 0;
}

.amazon {
  height: 4rem;
  width: 10rem;
}
</style>
