<template>
  <h1>The APP template</h1>

  <Footer />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Home from "@/components/Home.vue";
import Footer from "@/components/Footer.vue";
import Header from "@/components/Header.vue";

export default defineComponent({
  name: "App",
  components: { Home, Footer },
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

<style>
header.py-4 {
  height: 350px;
}
</style>
