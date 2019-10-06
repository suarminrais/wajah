<template>
  <section class="section wajah is-medium">
    <div class="container">
      <article class="media p-248">
        <figure class="media-left">
          <p class="image is-379x457">
            <img src="../assets/Group 42.png" />
          </p>
        </figure>
        <div class="media-content">
          <h1 class="title">PROFIL</h1>
          <div class="content">
            <p>Pasangan H. Andi Muhammad Ali Yusuf dan Hj. Andi Dalima Makkarodda membangun perekonomian keluarga dari bawah. Ketekunan kerja yang didukung semangat juang dalam kesederhanaan menurun ke anak-anaknya, tak terkecuali Andi Uchu. Sejak kecil Andi Uchu tidak hanya dituntut tekun dan disiplin belajar untuk meraih prestasi akademik semata, tapi juga mengimbanginya dengan tugas di rumah.</p>
          </div>
          <nav class="level is-mobile">
            <div class="level-left">
              <span class="level-item">
                <i class="fas fa-heart">&nbsp;Pengalaman Organisasi</i>
              </span>
              <span class="level-item">
                <i class="fas fa-heart">&nbsp;Karir Dan Bisnis</i>
              </span>
              <br />
            </div>
          </nav>
          <div class="content">
            <a class="button">Selengkapnya</a>
          </div>
        </div>
      </article>
    </div>
  </section>
</template>

<script>
export default {
  name: "Profil",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.wajah {
  background: url("../assets/svg/1.svg");
  background-position-x: 188;
  background-position-y: 344;
  background-repeat: no-repeat;
}
.p-248 {
  margin-left: 180px;
}
</style>
