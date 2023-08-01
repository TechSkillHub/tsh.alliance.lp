<template>
  <div>
    <Banner />
    <Planos />
    <Modalidades />
  </div>
</template>

<script>
import Banner from '@/components/banner/Banner.vue'
import Planos from '@/components/planos/Planos.vue'
import Modalidades from '@/components/modalidades/Modalidades.vue'

export default {
  data() {
    return {}
  },
  components: {
    Banner,
    Planos,
    Modalidades
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
