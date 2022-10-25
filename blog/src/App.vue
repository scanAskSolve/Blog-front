<template>
  <div>
    <vheader />
    <div id="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/resume">Resume</router-link>
    </div>
    <router-view />
    <Fooder />
  </div>
</template>

<script>
import vheader from "./components/Header.vue";
import Fooder from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    vheader,
    Fooder,
  },
};
</script>
<style></style>
