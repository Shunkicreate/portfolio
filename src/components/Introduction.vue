<template>
  <div class="introduction">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-10">
          <h2>This is portfolio of Shunki Tada</h2>
        </div>
        <div class="col-md-6 col-12">
          <div class="row justify-content-center row-content text-start gy-3">
            <div class="col-12">
              <h4>My first work</h4>
            </div>
            <div>
              This is my first work in programming. I love Mario so much that I
              was obsessed with it when I was a first year in college. The web
              site only works on a PC. The video is my tweet. The video is my
              tweet.
            </div>
            <div class="col-md-12 text-start">
              <div class="row justify-content-evenly text-start">
                <div class="col-md-2 col-auto text">
                  <a target="_blank" rel="noopener noreferrer" href="https://t.co/dNOr2MoAXa?amp=1">
                    <button type="button" class="btn btn-outline-secondary">website</button>
                  </a>
                </div>
                <div class="col-md-2 col-auto text">
                  <a
                    target="_blank"
                    rel="noopener noreferrer"
                    href="https://twitter.com/syunki____/status/1269528018076102657?s=20"
                  >
                    <button type="button" class="btn btn-outline-secondary">Video</button>
                  </a>
                </div>
              </div>
            </div>
            <div class="col-12">
              <h4>My Works</h4>
            </div>
            <div class="col-md-12">
              <ul>
                <li>
                  美女図鑑
                  <a
                    href="https://shunkicreate.github.io/beautiful_girl/"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <button
                      type="button"
                      class="btn btn-outline-secondary"
                    >https://shunkicreate.github.io/beautiful_girl/</button>
                  </a>
                </li>
                <li>晩飯</li>
              </ul>
            </div>
            <div class="col-12">
              <h4>Internships</h4>
            </div>
            <div class="col-md-12">
              <ul>
                <li>
                  <a
                    href="https://www.trypotlatch.com/"
                    target="_blank"
                    rel="noopener noreferrer"
                  >Potlatch</a> | Jan-Feb 2021
                </li>
                <li>
                  <a
                    href="https://hutzper.com/"
                    target="_blank"
                    rel="noopener noreferrer"
                  >Hutzper</a> | Aug- 2021
                </li>
                <li>
                  <a
                    href="https://simplise.jp/"
                    target="_blank"
                    rel="noopener noreferrer"
                  >Simplise</a> | Aug- 2021
                </li>
              </ul>
            </div>
            <div class="col-12">
              <h4>Who is he?</h4>
            </div>
            <div class="col-12">Shunki Tada is a programmer.</div>
            <div class="col-12">
              He can write basic HTML and CSS and he can create a website using
              Vue.js.
            </div>
            <div class="col-12">Moreover, he is familior with Python and C language.</div>
            <div class="col-12">
              <router-link
                to="/history"
                target="_top"
                class="nav-link active"
                aria-current="page"
              >Learn more</router-link>
            </div>
          </div>
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
.row-content {
  margin-top: 0;
  margin-bottom: 0;
}
</style>