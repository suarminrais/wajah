<template>
  <div class="container">
    <section class="hero is-medium video">
      <div class="hero-body">
          <div class="container">
            <div class="columns">
              <div class="column">
                <figure class="image is-128x128"><img class="is-rounded" src="https://bulma.dev/placeholder/pictures/bg_circle.svg?primary=00d1b2" alt=""></figure>                
              </div>
              <div class="column">
                <figure class="image is-16by9">
                  <iframe class="has-ratio" width="640" height="360" src="https://www.youtube.com/embed/YE7VzlLtp-4?showinfo=0" frameborder="0" allowfullscreen></iframe>
                </figure>
              </div>
            </div>
          </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Video',
  props: {
    msg: String
  }
}
</script>