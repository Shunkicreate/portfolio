<template>
  <div class="app">
    <div id="nav" class="shadow-sm">
      <ul class="nav justify-content-end">
        <li class="nav-item">
          <a
            href="https://shunkicreate.github.io/portfolio/"
            class="nav-link active"
            aria-current="page"
            >Home</a
          >
        </li>
        <li class="nav-item">
          <router-link to="/history" class="nav-link">History</router-link>
        </li>
      </ul>
    </div>
    <keep-alive>
      <router-view />
    </keep-alive>
    <Footer />
  </div>
</template>

// <script lang="ts">
import Footer from "../src/components/Footer.vue";

export default {
  name: "App",

  components: {
    Footer,
  },
};
</script>


<style lang="scss">
* {
  margin: 0;
  // background-color: #EFEFF0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  // background-color: #EFEFF0;
}

#nav {
  padding: 50px;
  background-color: #EFEFF0;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #c9c8c8;
    }
  }
}

a {
  font-weight: bold;
  color: #2c3e50;
}

.nav-link {
  font-family: serif, system-ui;
}
</style>
