<template>
  <section class="py-5">
    <h1 class="fw-bolder text-center">Examples</h1>
    <div
      id="carouselExampleControls"
      class="carousel slide carousel-dark"
      data-bs-ride="carousel"
    >
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img
            src="@/assets/images/Bathroom_mural.jpg"
            class="d-block"
            alt="..."
          />
        </div>
        <div class="carousel-item">
          <img
            src="@/assets/images/OldMacDonaldHadABand.jpg"
            class="d-block"
            alt="..."
          />
        </div>
        <div class="carousel-item">
          <img src="@/assets/images/Tracktors.jpg" class="d-block" alt="..." />
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExampleControls"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExampleControls"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Cara",
});
</script>

<style scoped>
@media only screen and (min-width: 480px) {
  .d-block {
    display: block;
    width: fit-content;
    height: 50vh;
    padding-left: 32.5%;
  }
}
/* Mobile Portrait Size to Mobile Landscape Size (devices and browsers) */
@media only screen and (max-width: 479px) {
  .d-block {
    display: block;
    width: fit-content;
    height: 30vh;
    padding-left: 10.9%;
  }
}
</style>
