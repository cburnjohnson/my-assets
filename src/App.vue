<template>
  <div id="app-container">
    <Navbar />
    <h1 class="heading">My Assets</h1>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar";

export default {
  name: "App",
  components: { Navbar }
};
</script>

<style lang="scss">
@import "./scss/main";
#app-container {
  height: 100vh;
  background-color: $main-bg;
}
</style>
