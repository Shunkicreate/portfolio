<template>
  <div class="app">
    <div id="nav" class="shadow-sm">
      <ul class="nav justify-content-end">
        <li class="nav-item">
          <a
            href="https://shunkis-portfolio.netlify.app/"
            class="nav-link active"
            aria-current="page"
          >Home</a>
        </li>
        <li class="nav-item">
          <router-link to="/" class="nav-link">demo home</router-link>
        </li>
        <li class="nav-item">
          <router-link to="/history" class="nav-link">History</router-link>
        </li>
        <li class="nav-item">
          <router-link to="/contact" class="nav-link">Contact</router-link>
        </li>
        <li class="nav-item">
          <router-link to="/about" class="nav-link">About</router-link>
        </li>
      </ul>
    </div>
    <transition name="fade">
      <router-view />
    </transition>
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
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: #efeff0;
}


#nav {
  padding: 50px;
  background-color: #efeff0;

  a {
    font-weight: bold;
    color: #2c3e50;
    transition: 1s;

    &.router-link-exact-active:visited {
      color: #c9c8c8;
    }
    &.router-link-active:hover {
      color: #2c3e50;
    }
    // &.router-link-exact-active:active {
    //   color: #ffc400;
    // }
    // &.router-link-exact-active:link {
    //   color: #942500;
    // }
  }
}



.nav-link {
  font-family: serif, system-ui;
}

.fade-enter-active,
.fade-leave-active {
  transition: opacity 3s;
}

.fade-enter-from,
.fade-leave-to {
  opacity: 0;
}
</style>
