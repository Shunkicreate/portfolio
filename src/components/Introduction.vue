<template>
  <div class="introduction">
    <div class="container">
      <div class="row justify-content-center row-content gy-3">
        <div class="col-12">
          <h2>This is portfolio of Shunki Tada, 多田駿希</h2>
        </div>
        <div class="col-12 text">
          <h4>Who is he?</h4>
        </div>
        <div class="col-12 text">Shunki Tada is a programmer.</div>
        <div class="col-12 text">
          He can write basic HTML and CSS and he can create a website using
          Vue.js.
        </div>
        <div class="col-12 text">
          Moreover, he is familior with Python and C language.
        </div>
        <div class="col-12 text">
          <router-link to="/history" target="_top" class="nav-link active" aria-current="page"
            >Learn more</router-link
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "@vue/runtime-core";

export default defineComponent({
  name: "Introduction",
});
</script>

<style>
h2 {
  font-family: serif, system-ui;
  padding: 2em;
}


.text {
  font-family: LinotypeUnivers-430Regular, "Gothic Medium BBB", 游ゴシック,
    "Yu Gothic", 游ゴシック体, YuGothic, "ヒラギノ角ゴ Pro W3", メイリオ, Meiryo,
    "ＭＳ Ｐゴシック", "MS PGothic", sans-serif;
}
.row-content{
  margin-top:0;
  margin-bottom:0;
}
</style>