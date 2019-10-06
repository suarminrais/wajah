<template>
  <section class="hero is-warning is-fullheight-with-navbar is-bold full">
    <div class="hero-head">
      <div class="container">
        <Navbar></Navbar>        
      </div>    
    </div>

    <div class="hero-body">
      <div class="container has-text-centered">
        <carousel perPage="1">
          <slide>
            Wajah
          </slide>
          <slide>
            Baru
          </slide>
        </carousel>
      </div>
    </div>
  </section>
</template>

<script>
import Navbar from './Navbar.vue'

export default {
  name: 'Head',
  props: {
    msg: String
  },
  components:{
    Navbar,
  }
}
</script>

<style scoped>
  .full{
    min-height: -webkit-fill-available !important;
  }
</style>