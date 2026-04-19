<script>
import AppHeader from "@/components/AppHeader.vue";
import { Toaster } from "vue-sonner";

export default {
  components: {
    AppHeader,
    Toaster,
  },
};
</script>

<template>
  <div id="app">
    <AppHeader />
    <div class="container mt-3">
      <router-view />
    </div>
    <Toaster position="top-left" richColors />
  </div>
</template>

<style>
.page {
  max-width: 400px;
  margin: auto;
}
</style>
