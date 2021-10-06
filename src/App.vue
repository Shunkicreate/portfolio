<template>
  <div class="app">
    <div id="nav" class="shadow-sm">
      <ul class="nav justify-content-end">
        <li class="nav-item">
          <router-link to="/" class="nav-link active" aria-current="page"
            >Home</router-link
          >
        </li>
        <li class="nav-item">
          <router-link to="/about" class="nav-link">History</router-link>
        </li>
      </ul>
    </div>
    <router-view />
    <Footer/>

  </div>
</template>

// <script lang="ts">
import Footer from '../src/components/Footer.vue'

export default {
  name: 'App',

  components: {
    Footer,
  },
}
</script>


<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: rgb(239, 239, 240);
}

#nav {
  padding: 50px;
  background-color: rgb(241, 241, 241);

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #c9c8c8;
    }
  }
}
* {
  margin: 0;
  font-family: LinotypeUnivers-430Regular, "Gothic Medium BBB", 游ゴシック,
    "Yu Gothic", 游ゴシック体, YuGothic, "ヒラギノ角ゴ Pro W3", メイリオ, Meiryo,
    "ＭＳ Ｐゴシック", "MS PGothic", sans-serif;
}

a {
    font-weight: bold;
    color: #2c3e50;

  }
</style>
