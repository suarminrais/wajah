<template>
  <div>
    <section>
      <img src="../assets/svg/Video.svg" alt />
    </section>
    <div class="container">
      <section class="hero is-medium video">
        <div class="hero-body">
          <div class="container">
            <div class="columns">
              <div class="column">
                <h2 class="title is-4">Lore</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat et itaque, hic neque molestiae, delectus consequatur inventore esse magni id cumque ipsum. Odio magnam quae in sit optio, voluptate excepturi?</p>
              </div>
              <div class="column">
                <figure class="image is-16by9">
                  <iframe
                    class="has-ratio"
                    width="640"
                    height="360"
                    src="https://www.youtube.com/embed/YE7VzlLtp-4?showinfo=0"
                    frameborder="0"
                    allowfullscreen
                  ></iframe>
                </figure>
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  name: "Video",
  props: {
    msg: String
  }
};
</script>