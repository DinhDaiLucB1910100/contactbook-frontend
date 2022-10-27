<script>
// import abc from  "./services/contact.service.js";
import AppHeader from "@/components/AppHeader.vue";
export default {
  // mounted () {
  //   abc.getAll(); 
  // },
  components: {
    AppHeader,
  },
}
</script>
<template>
  <div id="app">
    <AppHeader />
    <div class="container mt-3">
      <router-view />
    </div>
  </div>
</template>
<style>
.page {
  max-width: 400px;
  margin: auto;
}
</style>