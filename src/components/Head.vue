<template>
  <section class="hero is-fullheight-with-navbar is-bold">
    <div class="hero-head">
      <div class="container">
        <Navbar></Navbar>
      </div>
    </div>

    <div class="hero-body">
      <div class="container is-centered wajah-banner">
        <h1 class="title wajah-tesk">MUHAMMAD YUSUF</h1>
        <h2 class="subtitle wajah-sub">WAJAH BARU BULUKUMBA 2020</h2>
      </div>
    </div>
  </section>
</template>

<script>
import Navbar from "./Navbar.vue";

export default {
  name: "Head",
  props: {
    msg: String
  },
  components: {
    Navbar
  }
};
</script>

<style scoped>
.hero {
  background: url("../assets/Group 46.png");
  background-repeat: no-repeat;
  background-position: right top;
  background-size: contain;
}
.wajah-banner {
  margin-left: 180px;
}
.wajah-tesk {
  font-size: 69px;
  color: #132634;
  line-height: 79px;
}
.wajah-sub {
  font-size: 17px;
  color: #132634;
  line-height: 20px;
}
</style>