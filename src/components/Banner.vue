<template>
  <div class="banner">
    <div class="title">
      <h1 class="name">Lynn Speng</h1>
      <h3 class="name">Student</h3>
      <h3 class="name">Developer</h3>
    </div>
    <div class="illustration">
      <img src="../assets/illustration.svg" alt="illustration" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Banner",
};
</script>

<style>
.banner {
  width: 100%;
  height: 480px;
  background-color: #1b1b1b;
  color: white;
  box-sizing: border-box;
  padding: 100px 300px;
  display: flex;
}

.title {
  flex: 1;
  padding: 100px 50px;
}

.title {
  font-family: "Georgia";
}

.title h1 {
  font-size: 45px;
}

.title h3 {
  font-style: italic;
  font-weight: bold;
}

.illustration {
  flex: 1;
}

.illustration img {
  width: 500px;
  height: 400px;
  object-fit: fill;
}

.banner {
  padding: 50px 500px;
}
</style>
