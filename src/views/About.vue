<template>
  <div class="history">
    <div class="container">
      <div class="row text-center justify-content-center history_row">
        <div class="col-12">
          <h1 class="title" style="font-size: 6ex;">About me</h1>
        </div>
      </div>
      <History />
    </div>
    
  </div>
</template>

<style lang="scss">
</style>

<script lang="ts">
import { defineComponent ,ref} from 'vue';
import History from '../components/History.vue'

export default defineComponent({
  name: 'About',
  
  components: {
    History,
  }
});
</script>