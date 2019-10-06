<template>
  <div class="container">
    <section>
        <b-tabs position="is-centered" v-model="activeTab">
          <b-tab-item label="Visi" icon="google-photos">
            <Box></Box>
            <Box></Box>
            <Box></Box>
          </b-tab-item>
          <b-tab-item label="Misi" icon="library-music">
            <Box></Box>
          </b-tab-item>
        </b-tabs>
    </section>
  </div>
</template>

<script>
import Box from './Box'
export default {
  data() {
      return {
          activeTab: 0,
          showBooks: false
      }
  },
  components:{
    Box
  },
  name: 'Visi',
  props: {
    msg: String
  },
}
</script>