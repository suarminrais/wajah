<template>
  <footer class="footer">
    <div class="container">
      <div class="columns">
        <div class="column">
          <div class="buttons">
            <a class="kiri" href="#">
              <img src="../assets/svg/email.svg" alt />
            </a>
            <a class="kiri" href="#">
              <img src="../assets/svg/facebook.svg" alt />
            </a>
            <a class="kiri" href="#">
              <img src="../assets/svg/instagram.svg" alt />
            </a>
            <a class="kiri" href="#">
              <img src="../assets/svg/youtube.svg" alt />
            </a>
          </div>
        </div>
        <div class="column has-text-centered has-text-right-tablet">
          <img src="../assets/svg/logo.svg" alt />
        </div>
        <div class="column has-text-centered has-text-right-tablet">
          <img src="../assets/svg/2019.svg" alt />
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  props: {
    msg: String
  }
};
</script>

<style scoped>
.kiri {
  margin-left: 30px;
}
</style>