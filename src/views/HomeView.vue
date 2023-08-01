<template>
  <div>
    <Banner id="banner" />
    <Planos id="planos" />
  </div>
</template>

<script>
import Banner from '@/components/banner/Banner.vue'
import Planos from '@/components/planos/Planos.vue'

export default {
  data() {
    return {}
  },
  components: {
    Banner,
    Planos,
  },
  computed: {
    currentPage() {
      return this.$store.state.manager.currentPage
    }
  },
  mounted() {},
  methods: {},
  watch: {}
}
</script>

<style lang="scss" scoped></style>
