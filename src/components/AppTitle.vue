<script>
export default {
  data() {
    return {
      title: "La mia prima app con Vite!",
    };
  },
};
</script>

<template>
  <h1 class="title">{{ title }}</h1>
</template>

<style scoped>
.title {
  margin: 15px 0;

  font-size: 3rem;

  font-weight: bold;

  text-shadow: grey 1px 0 10px;
}
</style>
