<!-- ## SCRIPT -->
<script>
import AppTitle from "./components/AppTitle.vue";

export default {
  components: {
    AppTitle,
  },

  data() {
    return {};
  },
};
</script>

<!-- ## TEMPLATE -->
<template>
  <div class="container">
    <AppTitle></AppTitle>
  </div>
</template>

<!-- ## STYLE -->
<style>
@import url("./assets/main.css");

.container {
  display: flex;
  justify-content: center;

  width: 100%;
  height: 100vh;

  background-color: lightgray;
}
</style>
