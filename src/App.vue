<template>
  <div id="app">
    <Head></Head>
    <Sesi></Sesi>
    <Tagline></Tagline>
    <Visi></Visi>
    <Berita></Berita>
    <!-- <Testimoni></Testimoni> -->
    <Relawan></Relawan>
    <Video></Video>
    <Footer></Footer>
  </div>
</template>

<script>
import Head from "./components/Head";
import Sesi from "./components/Profil";
import Berita from "./components/Berita";
import Visi from "./components/Misi";
import Footer from "./components/Footer";
import Relawan from "./components/Relawan";
import Tagline from "./components/Tagline";
import Video from "./components/Video";
import Testimoni from "./components/Testimoni";

export default {
  name: "app",
  components: {
    Head,
    Sesi,
    Berita,
    Visi,
    Relawan,
    Footer,
    Video,
    Testimoni,
    Tagline
  }
};
</script>