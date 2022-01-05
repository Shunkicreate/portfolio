<template>
  <div class="history">
    <h1 class="title" style="font-size: 6ex;">History</h1>
    <div class="container">
      <div class="row text-start justify-content-center history_row">
        <div class="col-lg-3 col-12 subtitle">Hometown</div>
        <div class="col-lg-7 col-11 text-break history-text">
          I am from Toon City, Ehime Prefecture, Japan. 
        </div>
      </div>

      <div class="row text-start justify-content-center history_row">
        <div class="col-lg-3 col-12 subtitle">Educational Background</div>
        <div class="col-lg-7 col-11 text-break history-text">
          <ul>
          <li><a href="https://minamiyoshii-e.esnet.ed.jp/" target="_blank" rel="noopener noreferrer">Minami-yoshii Elementary School</a></li>
          <li><a href="https://shigenobu-j.esnet.ed.jp/" target="_blank" rel="noopener noreferrer">Shigenobu Junior High School</a></li>
          <li><a href="https://matsuyamahigashi-h.esnet.ed.jp/" target="_blank" rel="noopener noreferrer">Matsuyamahigashi High School</a></li>
          <li><a href="http://www.ritsumei.ac.jp/" target="_blank" rel="noopener noreferrer">Ritsumeikan University -the Faculty of Information Science and Engineering</a></li>
          </ul>
        </div>
      </div>

      <div class="row text-start justify-content-center history_row">
        <div class="col-lg-3 col-12 subtitle">Current</div>
        <div class="col-lg-7 col-11 text-break history-text">
          I am currently a member of the College of Information Science and
          Engineering, Ritsumeikan University. 
        </div>
      </div>
      <div class="row text-start justify-content-center history_row">
        <div class="col-lg-3 col-12 subtitle">What are you doing</div>
        <div class="col-lg-7 col-11 text-break history-text">
          I started programming when I entered university, and I am currently studying to become a programmer. First, I studied Processing, and then I realized the fun of programming. After that, I studied web front, Python, and so on, until now.
        </div>
      </div>
      <div class="row text-start justify-content-center history_row">
        <div class="col-lg-3 col-12 subtitle">Favorites</div>
        <div class="col-lg-7 col-11 text-break history-text">
          My favorite thing to do is to play games. I'm currently playing Haragami and Winning Eleven. I also like Splatoon, and I basically love Nintendo's Mario games. I also listen to music a lot, and am a fan of Mr. Children. I also listen to Vocaloid music, such as Hatsune Miku and Kagamine Rinren. I also like to read. My favorite authors are Kanae Minato and Kotaro Isaka, and I especially love Confessions and Desert.
        </div>
      </div>
      <div class="row text-start justify-content-center history_row">
        <div class="col-lg-3 col-12 subtitle">Towards the Future</div>
        <div class="col-lg-7 col-11 text-break history-text">
          I'm currently studying programming. I'm currently studying programming, but only because I want the ability to make interesting things. In other words, I don't like programming per se, but I like to use programming to create something. Therefore, I would like to create something that I find interesting in the future. If you have any questions, please feel free to contact me on any of the SNS below. Thank you for reading this far.
        </div>
      </div>

    </div>
  </div>
</template>

<style lang="scss">

.history_row {
  margin-top: 7em;
}

.subtitle {
  font-size: xx-large;
  font-family: serif,system-ui;

}

.history-text {
  font-family: 'MV Boil',"Objective", "游ゴシック体", "Yu Gothic", YuGothic, "ヒラギノ角ゴ Pro", "Hiragino Kaku Gothic Pro", "メイリオ", "Meiryo", sans-serif;
  line-height:2em;
}
</style>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'History',
});
</script>