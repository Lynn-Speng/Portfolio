<template>
  <div class="content">
    <div class="item">
      <h2>About Me</h2>
      <p>
        I’m Lynn Speng. This name is a variation of my real name(Shaopeng Ling)
        and is widely used on various social media and platforms to substitute
        my real name. As for the domain of the website “Ice Twilight”, it is
        just a combination of two irrelevant things to make it unique. 😘 And it
        also looks nice, right?
      </p>
    </div>
    <div class="item">
      <h2>Academics</h2>
      <p>
        An undergraduate student majoring in artificial intelligence at Xidian
        University.
      </p>
    </div>
    <div class="item">
      <h2>Hobbies</h2>
      <ul>
        <li>
          <p>Create something interesting.</p>
        </li>
        <li>
          <p>Learn something new and awesome.</p>
        </li>
        <li>
          <p>
            Listen to music, mostly modern classical music and new age music.
          </p>
        </li>
      </ul>
    </div>
    <div class="item">
      <h2>Contact Me</h2>
      <p>
        Email:
        <a href="mailto:Lynn.Speng@outlook.com">Lynn.Speng@outlook.com</a>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Content",
};
</script>

<style>
.content {
  padding: 50px 500px;
}

.item p {
  line-height: 140%;
  font-size: 18px;
  font-weight: 400;
  margin: 10px 15px;
}

@media screen and (max-width: 1200px) {
  .content {
    padding: 50px 100px;
  }

  .item p {
    margin: 8px 12px;
  }
}

@media screen and (max-width: 600px) {
  .content {
    padding: 35px 35px;
  }

  .item p {
    margin: 5px 10px;
  }
}

/* iPhone 5/SE */
@media screen and (max-width: 320px) {
  .content {
    padding: 20px 30px;
  }

  .item h2 {
    font-size: 22px;
  }
  .item p {
    font-size: 16px;
    margin: 5px 2px;
  }
}
</style>
