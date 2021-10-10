<template>
  <div class="bootstrap">
      <div class="container">
          <div class="row justify-content-center gy-3">
              <div class="col-12">
                  <h2>This is portfolio of Shunki Tada</h2>
              </div>
              <div class="col-12">
                  Shunki Tada is a programer.
              </div>
              <div class="col-12">
                  He can write basic HTML and CSS and he can create a website using Vue.js.
              </div>
              <div class="col-12">
                  Moreover, he is familer to Python and C language. 
              </div>

          </div>

      </div>
  </div>
</template>

<script>
import { defineComponent } from "@vue/runtime-core";

export default defineComponent({
    name: "MinBootstrap",

})
</script>

<style>
h2 {
  font-family: serif,system-ui;
  font-weight: lighter;
}
</style>