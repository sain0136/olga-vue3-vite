<template>
  <Navigation />
  <!-- Header - set the background image for the header in the line below-->
  <div class=".container-fluid">
    <img class="img-fluid" src="@/assets/images/background.jpg" alt="Header" />
  </div>
  <section class="py-4">
    <div class="container my-4">
      <div class="row justify-content-center">
        <div class="col-lg-6">
          <h2>Welcome I am Olga Permovich</h2>
          <p class="lead text-cente">
            I would like to introduce myslef I am Olga Permovich, on this site
            you can view my work and schedule comissions, paint events, and
            register for my scheduled classes! Hope you enjoy my work and I am
            looking foward to meet you!
          </p>
          <p class="mb-0">
            The universe is almost 14 billion years old, and, wow! Life had no
            problem starting here on Earth! I think it would be inexcusably
            egocentric of us to suggest that we're alone in the universe.
          </p>
          <hr />
        </div>
      </div>
    </div>
  </section>
  <Cara />
  <Footer />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Home from "@/components/Home.vue";
import Footer from "@/components/Footer.vue";
import Navigation from "@/components/Navigation.vue";
import Cara from "@/components/Cara.vue";
import imgUrl from "@/assets/images/background.jpg";

export default defineComponent({
  name: "App",
  components: { Home, Footer, Navigation, Cara },
  data() {
    return {
      name: "link",
    };
  },
  methods: {
    changeName(name: string) {
      this.name = name;
    },
  },
});
</script>

<style scoped>
@media only screen and (min-width: 992px) {
  .img-fluid {
    max-height: 350px;
    object-fit: cover;
    width: 100%;
  }
}
</style>
