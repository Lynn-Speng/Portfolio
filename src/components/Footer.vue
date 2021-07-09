<template>
  <div class="footer">
    <p>
      Built with
      <a href="https://cli.vuejs.org/">Vue.js</a> . Depolyed on
      <a href="https://vercel.com">Vercel</a>.
    </p>
    <p>
      View source code on
      <a href="https://github.com/LynnSpeng/Portfolio">Github</a>
    </p>
    <p>©2020 - 2021 Lynn Speng</p>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style>
.footer {
  padding: 10px 500px;
}
.footer p {
  text-align: center;
  text-decoration: blue;
  margin: 5px auto;
}

@media screen and (max-width: 1200px) {
  .footer {
    padding: 10px 50px;
  }
  .footer p {
    margin: 5px auto;
  }
}

@media screen and (max-width: 600px) {
  .footer {
    padding: 10px 20px;
  }
  .footer p {
    font-size: 16px;
    margin: 5px auto;
  }
}
</style>
