<template>
  <div id="app">
    <Head></Head>
    <Tentang></Tentang>
    <Footer></Footer>
  </div>
</template>

<script>
import Head from "./components/Head";
import Tentang from "./components/Tentang";
import Visi from "./components/Misi";
import Footer from "./components/Footer";

export default {
  name: "app",
  components: {
    Head,
    Visi,
    Footer,
    Tentang
  }
};
</script>