<script>
export default {
  name: "AppFooter",
  data() {
    return {
      infos: [
        {
          text: "ABOUT",
          item1:
            "Masterstudy is Education WordPress theme featured by Learning",
          item2: "Managment System (LMS) for onine education.",
          item3: "Developed by StylemixThemes.",
          item4: "",
        },
        {
          text: "CONTACT",
          item1: "USA, California 20, First Avenue, Claifornia",
          item2: "Tel.: +1 212 458 300",
          item3: "Fax: +1 212 375 24 14",
          item4: "info@masterstudy.com",
        },
        {
          text: "PAGES",
          item1: "Blog Courses",
          item2: "Home",
          item3: "Shortcodes",
          item4: "",
        },
        {
          text: "BLOG",
          item1: "Our main target is to`Developing Yourself as a Leader`",
          item2: "-August 9, 2018",
          item3: "Those Other College Expenses You Aren't Thinking About",
          item4: "-June 3, 2015",
        },
      ],
    };
  },
};
</script>

<template>
  <footer class="footer">
    <div class="row flex">
      <div
        class="col mt-5"
        v-for="(info, index) in infos"
        :key="index"
        :id="info.text"
      >
        <ul>
          <h2>{{ info.text }}</h2>
          <li>{{ info.item1 }}</li>
          <li>{{ info.item2 }}</li>
          <li>{{ info.item3 }}</li>
          <li>{{ info.item4 }}</li>
        </ul>
      </div>
      <div class="icons">
        <i class="fa-brands fa-facebook fa-xl"></i>
        <i class="fa-brands fa-twitter fa-xl"></i>
        <i class="fa-brands fa-instagram fa-xl"></i>
      </div>
    </div>
  </footer>
</template>

<style lang="scss">
@use "../style/generals.scss";

.footer {
  height: 400px;
  background-color: #f2b91e;
}

.flex {
  display: flex;
}

ul {
  list-style-type: none;
}
.icons {
  margin-left: 2rem;
  i {
    padding-left: 1rem;
  }
}
</style>
