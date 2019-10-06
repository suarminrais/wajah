<template>
    <b-navbar>
        <template slot="brand">
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <Strong>Wajah Baru</Strong>
            </b-navbar-item>
        </template>
        <!-- <template slot="start">
            <b-navbar-item href="#">
                Home
            </b-navbar-item>
            <b-navbar-item href="#">
                Documentation
            </b-navbar-item>
            <b-navbar-dropdown label="Info">
                <b-navbar-item href="#">
                    About
                </b-navbar-item>
                <b-navbar-item href="#">
                    Contact
                </b-navbar-item>
            </b-navbar-dropdown>
        </template> -->

        <template slot="end">
            <b-navbar-item>
              <strong>Profil</strong>
            </b-navbar-item>
            <b-navbar-dropdown label="Visi & Misi">
              <b-navbar-item>
                Visi
              </b-navbar-item>
              <b-navbar-item>
                Misi
              </b-navbar-item>
            </b-navbar-dropdown>
            <b-navbar-item tag="div">
                <div class="buttons">
                    <a class="button is-light">
                        Testimoni
                    </a>
                    <a class="button is-grey-light">
                        Video
                    </a>
                </div>
            </b-navbar-item>
        </template>
    </b-navbar>
</template>

<script>
export default {
  name: 'Navbar',
  props: {
  }
}
</script>
