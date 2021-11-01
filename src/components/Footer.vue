<template>
  <!-- Footer-->
  <footer class="py-4 bg-dark">
    <div class="container">
      <p class="m-0 text-center text-white">
        Copyright &copy; Your Website 2021
      </p>
    </div>
  </footer>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Footer",
});
</script>

<style scoped>
footer.py-4 {
  position: fixed;
  bottom: 0;
  width: 100%;
}
</style>
