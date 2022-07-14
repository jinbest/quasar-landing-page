<template>
  <div class="quasar-header">
    <img src="../assets/quasar-logo.png" alt="logo" />
  </div>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "HeaderPage",
});
</script>

<style lang="scss" scoped>
.quasar-header {
  width: 100vw;
  height: 60px;
  padding: 0 50px;
  display: flex;
  align-items: center;
  position: fixed;
  left: 0%;
  top: 0;
  z-index: 1000;

  img {
    height: 25px;
  }

  @media (max-width: 960px) {
    padding: 0 25px;
  }
}
</style>
