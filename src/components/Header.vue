<template>
  <!-- Header - set the background image for the header in the line below-->
  <header
    class="py-4 bg-image-full"
    :style="{
      backgroundImage: 'url(' + require('./assets/images/background.jpg') + ')',
    }"
  ></header>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Header",
});
</script>

<style scoped></style>
