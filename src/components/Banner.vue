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
  height: 600px;
  background-color: #1b1b1b;
  color: white;
  box-sizing: border-box;
  padding: 50px 500px;
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

@media screen and (max-width: 1200px) {
  .banner {
    height: 320px;
    padding: 30px 50px;
  }

  .title {
    flex: 1;
    padding: 10px 50px;
  }

  .illustration {
    flex: 1;
    /* display: none; */
  }

  .illustration img {
    width: 313px;
    height: 250px;
    object-fit: fill;
  }
}

@media screen and (max-width: 600px) {
  .banner {
    height: 240px;
    padding: 10px 30px;
  }

  .title {
    flex: 1;
    padding: 10px 5px;
  }

  .illustration {
    flex: 1;
    display: none;
  }

  .illustration img {
    width: 500px;
    height: 400px;
    object-fit: fill;
  }
}

/* iPhone 5/SE */
@media screen and (max-width: 320px) {
  .banner {
    height: 220px;
    padding: 8px 15px;
  }

  .title {
    flex: 1;
    padding: 10px 5px;
  }

  .title h1 {
    font-size: 30px;
  }

  .title h3 {
    font-size: 22px;
  }

  .illustration {
    flex: 1;
    display: none;
  }
}
</style>
