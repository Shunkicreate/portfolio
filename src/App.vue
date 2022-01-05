<template>
  <div class="app">
    <div id="nav" class="shadow-sm">
      <ul class="nav justify-content-end">
        <li class="nav-item">
          <router-link to="/" class="nav-link" active-class="active-link">Home</router-link>
        </li>
        <li class="nav-item">
          <router-link to="/history" class="nav-link" active-class="active-link">History</router-link>
        </li>
        <li class="nav-item">
          <router-link to="/contact" class="nav-link" active-class="active-link">Contact</router-link>
        </li>
        <li class="nav-item">
          <router-link to="/about" class="nav-link" active-class="active-link">About me</router-link>
        </li>
      </ul>
    </div>
    <transition name="fade">
      <router-view />
    </transition>
    <Footer />
  </div>
</template>

<script lang="ts">
import Footer from "../src/components/Footer.vue";

export default {
  name: "App",

  components: {
    Footer,
  },
};
</script>


<style lang="scss">
@import "./main.scss";
</style>
