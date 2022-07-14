<template>
  <q-layout view="lHh Lpr lFf">
    <HeaderPage />

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import { defineComponent } from "vue";
import HeaderPage from "../components/HeaderPage.vue";

export default defineComponent({
  name: "MainLayout",
  components: {
    HeaderPage,
  },
});
</script>
