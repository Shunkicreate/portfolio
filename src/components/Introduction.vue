<template>
  <div class="introduction">
    <div class="container">
      <div class="row justify-content-center gy-3">
        <div class="col-12">
          <h2>This is portfolio of Shunki Tada</h2>
        </div>
        <div class="col-12">
          <h4>Who is he?</h4>
        </div>
        <div class="col-12">Shunki Tada is a programer.</div>
        <div class="col-12">
          He can write basic HTML and CSS and he can create a website ueing
          Vue.js.
        </div>
        <div class="col-12">
          Moreover, he is familer to Python and C language.
        </div>
        <div class="col-12">
          <router-link to="/about" class="nav-link active" aria-current="page"
            >Learn more</router-link
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { defineComponent } from "@vue/runtime-core";

export default defineComponent({
  name: "Introduction",
});
</script>

<style>
a {
  font-weight: bold;
  color: #2c3e50;
}
.router-link-exact-active {
  color: #c9c8c8;
}
</style>