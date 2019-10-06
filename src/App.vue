<template>
  <div id="app">
    <Head></Head>
    <Sesi></Sesi>
    <Berita></Berita>
    <Visi></Visi>
    <Testimoni></Testimoni>
    <Relawan></Relawan>
    <Video></Video>
    <Footer></Footer>
  </div>
</template>

<script>

import Head from './components/Head'
import Sesi from './components/Sesi'
import Berita from './components/Berita'
import Visi from './components/Visi'
import Footer from './components/Footer'
import Relawan from './components/Relawan'
import Video from './components/Video'
import Testimoni from './components/Testimoni'

export default {
  name: 'app',
  components: {
    Head, Sesi, Berita,
    Visi, Relawan, Footer,
    Video, Testimoni
  }
}
</script>