<template>
  <section class="hero">
    <div class="hero-head">
      <div class="container">
        <h1 class="title has-text-centered">Testimoni</h1>
      </div>
    </div>
    <div class="hero-body">
      <div class="container">
        <carousel perPage="1">
          <slide>
            <div class="columns">
                <div class="column is-6">
                  <figure class="image is-128x128"><img class="is-rounded" src="https://bulma.dev/placeholder/pictures/bg_circle.svg?primary=00d1b2" alt=""></figure>
                </div>
                <div class="column is-6">
                  <article class="message">
                    <div class="message-body">
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit. <strong>Pellentesque risus mi</strong>, tempus quis placerat ut, porta nec nulla. Vestibulum rhoncus ac ex sit amet fringilla. Nullam gravida purus diam, et dictum <a>felis venenatis</a> efficitur. Aenean ac <em>eleifend lacus</em>, in mollis lectus. Donec sodales, arcu et sollicitudin porttitor, tortor urna tempor ligula, id porttitor mi magna a neque. Donec dui urna, vehicula et sem eget, facilisis sodales sem.
                    </div>
                  </article>
                </div>
            </div>
          </slide>
          <slide>
            <div class="columns">
                <div class="column is-6">
                  <figure class="image is-128x128"><img class="is-rounded" src="https://bulma.dev/placeholder/pictures/bg_circle.svg?primary=00d1b2" alt=""></figure>
                </div>
                <div class="column is-6">
                  <article class="message">
                    <div class="message-body">
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit. <strong>Pellentesque risus mi</strong>, tempus quis placerat ut, porta nec nulla. Vestibulum rhoncus ac ex sit amet fringilla. Nullam gravida purus diam, et dictum <a>felis venenatis</a> efficitur. Aenean ac <em>eleifend lacus</em>, in mollis lectus. Donec sodales, arcu et sollicitudin porttitor, tortor urna tempor ligula, id porttitor mi magna a neque. Donec dui urna, vehicula et sem eget, facilisis sodales sem.
                    </div>
                  </article>
                </div>
            </div>
          </slide>
        </carousel>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Testimoni',
  props: {
    msg: String
  }
}
</script>