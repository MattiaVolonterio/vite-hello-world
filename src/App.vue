<!-- ## SCRIPT -->
<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  components: {
    AppTitle,
    AppHero,
  },

  data() {
    return {};
  },
};
</script>

<!-- ## TEMPLATE -->
<template>
  <div class="main-container">
    <AppTitle></AppTitle>
    <AppHero></AppHero>
  </div>
</template>

<!-- ## STYLE -->
<style>
@import url("./assets/main.css");

.main-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  gap: 50px;

  width: 100%;
  height: 100vh;

  background-color: lightgray;
}
</style>
