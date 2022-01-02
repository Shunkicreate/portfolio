<template>
  <div class="home">
    <h1 class="title" style="font-size: 6ex;">Home</h1>
    <Carousel/>
    <Introduction/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Introduction from '../components/Introduction.vue'
import Carousel from '../components/Carousel.vue'

export default defineComponent({
  name: 'Home',
  components: {
    Introduction,
    Carousel,
  },
});
</script>

<style>

</style>
