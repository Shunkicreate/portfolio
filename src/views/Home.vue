<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <h1 class="title" style="font-size: 6ex;">Home</h1>
    <Carousel/>
    <Introduction/>
    <!-- <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/> -->
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
// import HelloWorld from '../components/HelloWorld.vue'; // @ is an alias to /src
import Introduction from '../components/Introduction.vue'
import Carousel from '../components/Carousel.vue'

export default defineComponent({
  name: 'Home',
  components: {
    // HelloWorld,
    Introduction,
    Carousel,
  },
});
</script>

<style>

</style>
