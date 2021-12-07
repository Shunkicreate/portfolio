<template>
  <div class="home">
    <h1 class="title" style="font-size: 6ex">Contact</h1>
    <div class="container">
      <div class="row justyfy-content-center">
        <div class="col">
          Thank you for visiting Shunki Tada's website. Please feel free to
          contact us if you have any questions or concerns about our work.
          Please note that * is a required field.
        </div>
        <div class="col-12">
          <div class="card" style="width: 80%">
            <div class="card-body">
              <h5 class="card-title">Special title treatment</h5>
              <p class="card-text">
                With supporting text below as a natural lead-in to additional
                content.
              </p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
          </div>
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
h1 {
  padding-top: 0.5em;
  font-family: serif, system-ui;
}
</style>
