<template>
  <section class="section">
    <div class="container has-text-centered">
      <div class="columns">
        <div class="column bg-pro">
          <div class="level">
            <div class="level-item">
              <figure class="image is-264x270">
                <img class="is-rounded" src="../assets/Group 43.png" alt />
              </figure>
            </div>
          </div>
          <div class="content is-large">
            <strong>
              <i>
                Bulukumba Sejahtera, Mandiri, Inovatif, Unggul, Berkarakter dan
                <br />Berkeadilan
              </i>
            </strong>
          </div>
          <h5 class="subtitle is-6">- Muhammad Yusuf -</h5>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Relawan",
  props: {
    msg: String
  }
};
</script>
<style scoped>
.bg-pro {
  background: url("../assets/svg/tanda kutip.svg");
  background-repeat: no-repeat;
  background-position: bottom;
  background-position-x: 120px;
}
</style>