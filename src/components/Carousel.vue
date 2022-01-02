<template>
  <div class="carousel">
    <div class="container">
      <div class="row justify-content-center carousel_img">
        <div class="col-md-8 col-12 ">
          <div
            id="carouselExampleFade"
            class="carousel slide carousel-fade"
            data-bs-ride="carousel"
          >
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="@/assets/image(1).webp" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="@/assets/image(2).webp" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="@/assets/image(3).webp" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="@/assets/image(4).webp" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="@/assets/image(5).webp" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="@/assets/image(6).webp" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="@/assets/image(7).webp" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="@/assets/image(8).webp" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="@/assets/image(9).webp" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="@/assets/image(10).webp" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="@/assets/image(11).webp" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="@/assets/image(12).webp" class="d-block w-100" alt="" />
              </div>
            </div>
            <a
              class="carousel-control-prev "
              href="#carouselExampleFade"
              role="button"
              data-bs-slide="prev"
            >
              <span
                class="carousel-control-prev-icon button"
                aria-hidden="true"
              ></span>
              <!-- <span class="visually-hidden">Previous</span> -->
            </a>
            <a
              class="carousel-control-next "
              href="#carouselExampleFade"
              role="button"
              data-bs-slide="next"
            >
              <span
                class="carousel-control-next-icon button"
                aria-hidden="true"
              ></span>
              <!-- <span class="visually-hidden">Next</span> -->
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "@vue/runtime-core";

export default defineComponent({
  name: "Carousel",
});
</script>

<style>


img {
  margin-top: 1em;
  margin-bottom: 2em;
}

.button {
  background:none;
}



.carousel_img{
  margin:0;
}
</style>