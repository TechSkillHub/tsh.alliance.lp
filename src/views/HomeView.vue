<template>
  <div>
    <Banner id="banner" />
    <Planos id="planos" />
    <Carousel id="carousel" />
    <Cards id="cards" />
    <AboutUs id="about" />
  </div>
</template>

<script>
import Banner from '@/components/banner/Banner.vue'
import Planos from '@/components/planos/Planos.vue'
import Carousel from '@/components/carousel/Carousel.vue'
import Cards from '@/components/cards/Cards.vue'
import AboutUs from '@/components/aboutUs/AboutUs.vue'

export default {
  data() {
    return {}
  },
  components: {
    Banner,
    Planos,
    Carousel,
    Cards,
    AboutUs
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
