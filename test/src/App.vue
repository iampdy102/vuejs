<template>
  <div id="app">
    <tHeader />
    <div id="content" class="content">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
import tHeader from "./components/layout/tHeader.vue";
export default {
  name: "App",
  components: {
    tHeader,
  },
};
</script>

<style>
</style>