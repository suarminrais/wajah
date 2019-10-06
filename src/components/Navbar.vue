<template>
  <b-navbar>
    <template slot="brand">
      <b-navbar-item tag="router-link" :to="{ path: '/' }">
        <img src="./../assets/svg/logo.svg" />
      </b-navbar-item>
    </template>
    <template slot="end">
      <b-navbar-item>
        <a class="clean">Profil</a>
      </b-navbar-item>
      <b-navbar-item>
        <a class="clean">Visi & Misi</a>
      </b-navbar-item>
      <b-navbar-item>
        <a class="clean">Berita</a>
      </b-navbar-item>
      <b-navbar-item>
        <a class="clean">Testimoni</a>
      </b-navbar-item>
      <b-navbar-item>
        <a class="clean">Video</a>
      </b-navbar-item>
    </template>
  </b-navbar>
</template>

<script>
export default {
  name: "Navbar",
  props: {}
};
</script>

<style scoped>
.clean {
  text-decoration-color: whitesmoke;
  color: whitesmoke;
}
</style>