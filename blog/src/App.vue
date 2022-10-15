<template>
  <div>
    <Header />
    <div id="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </div>
    <router-view />
    <Fooder />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Fooder from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Fooder,
  },
};
</script>
<style></style>
