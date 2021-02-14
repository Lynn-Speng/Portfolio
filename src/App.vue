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
body {
  margin: 0;
}

a {
  text-decoration: none;
}
</style>
