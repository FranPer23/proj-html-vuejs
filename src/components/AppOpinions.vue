<script>
export default {
  name: "AppCourses",
};
</script>

<template>
  <div class="container">
    <div class="row">
      <div class="col">
        <div class="opinion-card flex">
          <div class="inner-col-left">
            <i class="fa-solid fa-briefcase fa-2xl"></i>
          </div>
          <div class="inner-col-right">
            <h5>Entrepreneurship</h5>
            <p>
              Vestibulum vitae aliquam nunc. Suspendisse mollis metus ac tellus
              egestas pharetra. Suspendisse at viverra purus. Pellentesque nec
              posuere ligula, eu congue leo. Integer vulputate tempor arcu.
              Vestibulum vulputate
            </p>
          </div>
        </div>
        <div class="opinion-card flex">
          <div class="inner-col-left">
            <i class="fa-solid fa-thumbs-up fa-2xl"></i>
          </div>
          <div class="inner-col-right">
            <h5>Accelerated learning</h5>
            <p>
              Vestibulum vitae aliquam nunc. Suspendisse mollis metus ac tellus
              egestas pharetra. Suspendisse at viverra purus. Pellentesque nec
              posuere ligula, eu congue leo. Integer vulputate tempor arcu.
              Vestibulum vulputate
            </p>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="opinion-card flex">
          <div class="inner-col-left">
            <i class="fa-solid fa-rocket fa-2xl"></i>
          </div>
          <div class="inner-col-right">
            <h5>Productivity</h5>
            <p>
              Vestibulum vitae aliquam nunc. Suspendisse mollis metus ac tellus
              egestas pharetra. Suspendisse at viverra purus. Pellentesque nec
              posuere ligula, eu congue leo. Integer vulputate tempor arcu.
              Vestibulum vulputate
            </p>
          </div>
        </div>
        <div class="opinion-card flex">
          <div class="inner-col-left">
            <i class="fa-solid fa-gear fa-2xl"></i>
          </div>
          <div class="inner-col-right">
            <h5>Life Coaching</h5>
            <p>
              Vestibulum vitae aliquam nunc. Suspendisse mollis metus ac tellus
              egestas pharetra. Suspendisse at viverra purus. Pellentesque nec
              posuere ligula, eu congue leo. Integer vulputate tempor arcu.
              Vestibulum vulputate
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.opinion-card {
  padding: 1.25rem;
  padding-top: 2rem;
  margin-top: 1.25rem;
  margin-bottom: 1.25rem;
  border: 1px solid white;
  border-left-width: 0.25rem;
  border-radius: 0.25rem;
  box-shadow: 5px 5px 15px 5px #ececec;
}

.flex {
  display: flex;
  border-left-color: #f0ad4e;
}
.inner-col-left {
  width: 10%;
  padding-top: 0.5rem;
  i {
    color: #f0ad4e;
  }
}

.inner-col-right {
  width: 80%;
  padding-left: 0.5rem;
}

i {
  padding-left: 1rem;
}
</style>
