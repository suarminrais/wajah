<template>
  <div class="hello">
    <section class="section">
      <div class="container">
        <h2 class="title has-text-centered">BERITA TERBARU</h2>
        <div class="columns is-multiline">
          <div class="column is-6-tablet is-3-desktop">
            <div class="card" style="height: 100%">
              <div class="card-image">
                <a href="#">
                  <img src="../assets/Mask Group 2.png" alt />
                </a>
              </div>
              <div class="card-content">
                <div class="block">
                  <small class="is-size-7">25 Jun 2019 | By Dinesh Chugtai</small>
                </div>
                <h5 class="title is-6">
                  <a href="#">Why I'm the Best Programmer Ever</a>
                </h5>
                <p>I feel like not everybody outside of Pied Piper knows it, so I wanted to make it clear why I'm the best programmer in the world.</p>
              </div>
            </div>
          </div>
          <div class="column is-6-tablet is-3-desktop">
            <div class="card" style="height: 100%">
              <div class="card-image">
                <a href="#">
                  <img src="../assets/Mask Group 3.png" alt />
                </a>
              </div>
              <div class="card-content">
                <div class="block">
                  <small class="is-size-7">25 Jun 2018 | By Bertram Gilfoyle</small>
                </div>
                <h5 class="title is-6">
                  <a href="#">Secrets of Decentralization</a>
                </h5>
                <p>What makes decentralization so great? Let me enlighten you with my wisdom</p>
              </div>
            </div>
          </div>
          <div class="column is-6-tablet is-3-desktop">
            <div class="card" style="height: 100%">
              <div class="card-image">
                <a href="#">
                  <img src="../assets/Mask Group 4.png" alt />
                </a>
              </div>
              <div class="card-content">
                <div class="block">
                  <small class="is-size-7">25 Jun 2018 | By Monica Hall</small>
                </div>
                <h5 class="title is-6">
                  <a href="#">How Our ICO Almost Failed</a>
                </h5>
                <p>This is a short story about how we uncovered an insane problem with our ICO, fixed it, and still managed to secure vast funding.</p>
              </div>
            </div>
          </div>
          <div class="column is-6-tablet is-3-desktop">
            <div class="card" style="height: 100%">
              <div class="card-image">
                <a href="#">
                  <img src="../assets/Mask Group 4.png" alt />
                </a>
              </div>
              <div class="card-content">
                <div class="block">
                  <small class="is-size-7">25 Jun 2018 | By Monica Hall</small>
                </div>
                <h5 class="title is-6">
                  <a href="#">How Our ICO Almost Failed</a>
                </h5>
                <p>This is a short story about how we uncovered an insane problem with our ICO, fixed it, and still managed to secure vast funding.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="buttons is-centered">
          <a class="button is-primary is-large" href="#">Lebih Lanjut</a>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Berita",
  props: {
    msg: String
  }
};
</script>

<style scoped>
.is-primary {
  background-color: #292929eb !important;
  color: antiquewhite !important;
}
a {
  color: #292929eb !important;
}
</style>