<template>
  <Section class="py-2">
    <div
      id="carouselExampleSlidesOnly"
      class="carousel slide"
      data-bs-ride="carousel"
    >
      <h1 class="text-center">Portfolio</h1>
      <div class="carousel-inner py-2" id="Dave">
        <div class="carousel-item active">
          <img src="@/assets/images/Bathroom_mural.jpg" alt="..." />
        </div>
        <div class="carousel-item">
          <img src="@/assets/images/Tracktors.jpg" alt="..." />
        </div>
        <div class="carousel-item">
          <img src="@/assets/images/OldMacDonaldHadABand.jpg" alt="..." />
        </div>
      </div>
    </div>
  </Section>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Cara",
});
</script>

<style scoped>
@media only screen and (max-width: 959px) {
  #Dave > .imgD > img {
    display: block !important;
    width: fit-content !important;
    height: 40vh !important;
    padding-left: 32.5% !important;
  }
}

/* Tablet Portrait size to standard 960 (devices and browsers) */
@media only screen and (min-width: 768px) and (max-width: 959px) {
  #Dave > .imgD > img {
    display: block !important;
    width: fit-content !important;
    height: 40vh !important;
    padding-left: 32.5% !important;
  }
}

/* All Mobile Sizes (devices and browser) */
@media only screen and (max-width: 767px) {
  #Dave > .imgD > img {
    display: block !important;
    width: fit-content !important;
    height: 40vh !important;
    padding-left: 32.5% !important;
  }
}

/* Mobile Landscape Size to Tablet Portrait (devices and browsers) */
@media only screen and (min-width: 480px) and (max-width: 767px) {
  #Dave > .imgD > img {
    display: block !important;
    width: fit-content !important;
    height: 40vh !important;
    padding-left: 32.5% !important;
  }
}

/* Mobile Portrait Size to Mobile Landscape Size (devices and browsers) */
@media only screen and (max-width: 479px) {
  #Dave > .imgD > img {
    display: block !important;
    width: fit-content !important;
    height: 40vh !important;
    padding-left: 32.5% !important;
  }
}
</style>
