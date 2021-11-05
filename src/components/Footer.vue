<template>
  <!-- Footer-->
  <footer class="py-4 mt-5 bg-dark">
    <div class="container">
      <p class="m-0 text-center text-white">
        Copyright &copy; Davinci's Developers 2021
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
  position: sticky;
  bottom: 0;
  width: 100%;
}
</style>
