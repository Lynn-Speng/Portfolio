<template>
  <main>
    <div class="container">
      <Banner />
      <Content />
      <Footer />
    </div>
  </main>
</template>

<script>
import Banner from "./components/Banner.vue";
import Content from "./components/Content.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Banner,
    Content,
    Footer,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Newsreader:ital,wght@0,400;0,600;0,700;1,600&display=swap");
body {
  padding: 0;
  margin: 0;
  font-family: "Newsreader", serif;
}

a {
  text-decoration: none;
}
</style>
