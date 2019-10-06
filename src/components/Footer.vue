<template>
  <footer class="footer">
    <div class="container">
      <div class="level">
        <div class="level-left">
          <div class="level-item"><a class="title is-4" href="#">Wajah Baru</a></div>
        </div>
        <div class="level-right"><a class="level-item" href="#">Features</a><a class="level-item" href="#">Enterprise</a><a class="level-item" href="#">Support</a><a class="level-item" href="#">ICO</a></div>
      </div>
      <hr>
      <div class="columns">
        <div class="column">
          <div class="buttons"><a class="button" href="#"><img src="../assets/twitter.svg" alt=""></a><a class="button" href="#"><img src="../assets/facebook-f.svg" alt=""></a><a class="button" href="#"><img src="../assets/instagram.svg" alt=""></a></div>
        </div>
        <div class="column has-text-centered has-text-right-tablet">
          <p class="subtitle is-6">&copy; 2019 Wajah Baru. All right reserved.</p>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    msg: String
  }
}
</script>