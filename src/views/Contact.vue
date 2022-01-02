<template>
  <div class="home">
    <h1 class="title" style="font-size: 6ex">Contact</h1>
    <div class="container">
      <div class="row justify-content-center text-start">
        <div class="col-10 card-class">
          <div
            class="card text-dark bg-light border-dark"
            style="width: 100%; heighy"
          >
            <div class="card-header">
              <h4 class="card-title text-center">
                Drop a line! <br /><br /><br />Let's make wonderful treasure together!
              </h4>
            </div>
          </div>
        </div>
        <div class="col-10 gy-5"><h3>How to contact me</h3></div>
        <div class="col-10 gy-3">
          <ol>
            <li class="contact-list">Cluck below icons.</li>
            <li class="contact-list">Send DM.</li>
          </ol>
        </div>
        <div class="col-md-7 col-auto description">
          I always use Twitter, Imstagram, so if you select these SNS, I will
          respond as soon as possible.<br>
          if you want to check my skils, please click below github icon. Almost all my programming code is uploaded to here. <br>
          Thank you for visiting Shunki Tada's website. Please feel free to
          contact me if you have any questions or concerns about my work.
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Home",
});
</script>

<style>

.home {
  font-family: serif, system-ui;
}

.card-title {
  padding: 5em 0;
}

.contact-list {
  font-size: 1.6rem;
  padding: 0.3em;
}

.description{
  line-height:1.8em;
  margin:3em;
}

.card-class{
  margin: 4.5em;
}

</style>
