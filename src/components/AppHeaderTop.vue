<script>
export default {
  name: "AppHeaderTop",
  data() {
    return {
      links: [
        {
          text: "Courses",
          url: "#",
          current: false,
        },
        {
          text: "Course Formats",
          url: "#",
          current: false,
        },
        {
          text: "Add Course",
          url: "#",
          current: false,
        },
        {
          text: "Pages",
          url: "#",
          current: false,
        },
        {
          text: "Demos",
          url: "#",
          current: true,
        },
      ],
    };
  },
};
</script>

<template>
  <header class="header">
    <nav class="head-container flex">
      <div class="head-item">
        <img class="logo" src="../assets/img/MasterStudy-1.svg" alt="" />
      </div>
      <ul class="flex">
        <li v-for="link in links" :class="link.current ? 'active' : ''">
          <a :href="link.url">{{ link.text }}</a>
        </li>
      </ul>

      <div class="icons head-item">
        <i class="fa-brands fa-linkedin"></i>
        <i class="fa-brands fa-instagram"></i>
        <i class="fa-brands fa-facebook"></i>
        <i class="fa-brands fa-twitter"></i>
      </div>
    </nav>
  </header>
</template>

<style lang="scss" scoped>
.header {
  height: 100px;
  ul {
    list-style-type: none;
  }

  a {
    text-decoration: none;
    color: black;
  }
}
.flex li.active a {
  position: relative;
}

.flex li.active a::after {
  content: "";
  position: absolute;
  left: 0;
  bottom: -7px;
  width: 100%;
  height: 3px;
  background-color: #f2b91e;
}

.head-item {
  margin-top: 0.5rem;
  margin-left: 1rem;
}
.flex {
  display: flex;
  align-items: center;
  justify-content: center;
  padding-top: 1.5rem;
}

li,
i {
  padding-left: 1rem;
}

.logo {
  margin-right: 10rem;
  margin-left: 10rem;
}
</style>
