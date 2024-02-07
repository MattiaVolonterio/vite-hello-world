<script>
export default {
  data() {
    return {};
  },
};
</script>

<template>
  <div class="container">
    <div class="logo-container">
      <img
        src="../assets/img/vite-logo.svg"
        alt="vite-logo"
        class="hero-logo"
      />
    </div>
    <div class="text-container">
      <h2 class="hero-title">Questo è un paragrafo di prova</h2>
      <p class="hero-par">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugiat ut
        perspiciatis sed. Laborum, fugit quia quas distinctio molestiae sunt
        odio quos suscipit, nihil minus vero dolorum nisi at, sit a.
      </p>
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  justify-content: space-between;
  width: 60%;
  height: 400px;
  border-radius: 20px;

  background: linear-gradient(to bottom right, #bc35fe, #4dc2ff);
}

.logo-container {
  height: 100%;
  padding: 30px;
}

.hero-logo {
  height: 100%;
}

.text-container {
  display: flex;
  flex-direction: column;
  gap: 30px;

  padding: 30px;
}

.hero-title {
  font-size: 2rem;
}
</style>
