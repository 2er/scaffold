<template>
  <div class="home_container">
    <img src="../../images/logo.png"/>
  </div>
</template>

<script>
import { mapState, mapActions } from 'vuex'
export default {
  data () {
    return {
    }
  },
  created () {
  },
  mounted () {
  },
  components: {
  },
  computed: {
    ...mapState([
    ])
  },
  watch: {
  },
  methods: {
    ...mapActions({
    })
  }
}

</script>

<style lang="scss" scoped>
  @import '../../style/mixin';
  .home_container{
    text-align: center;
    img{
      margin-top: 50%;
    }
  }
</style>
