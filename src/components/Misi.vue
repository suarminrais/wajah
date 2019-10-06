<template>
  <section class="section wajah is-medium">
    <div class="container has-text-centered">
      <div class="columns wajah2">
        <div class="column"></div>
        <div class="column">
          <article class="media">
            <div class="media-content">
              <h1 class="title">Visi & Misi</h1>
              <div class="content">
                <ol type="1">
                  <li>Mendorong kemandiran sumber daya manusia Bulukumba.</li>
                  <li>Memacu pertumbuhan ekonomi yang berbasis pada potensi lokal.</li>
                  <li>Menyediakan pelayanan pendidikan dan kesehatan yang bermutu dan terjangkau</li>
                  <li>Mengembangkan sistem pelayanan masyarakat yang berkeadilan</li>
                  <li>Menjaga keselarasan pembangunan dengan kelesetarian lingkungan</li>
                  <li>Mengembangkan politik yang akomodatif</li>
                </ol>
              </div>
              <div class="content">
                <a class="button is-large">Selengkapnya</a>
              </div>
            </div>
          </article>
        </div>
        <div class="column"></div>
      </div>
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
  background: url("../assets/Group 44.png");
  background-size: contain;
  background-repeat: no-repeat;
  background-position: bottom left top;
}
.wajah2 {
  background: url("../assets/svg/1.svg");
  background-repeat: no-repeat;
  background-position: right top;
}
</style>
