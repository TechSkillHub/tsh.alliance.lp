<template>
  <div>
    <Banner />
    <Planos />
    <Modalidades />
    <Personal />
    <Grade />
    <Instalacao />
    <Whatsapp />
  </div>
</template>

<script>
import Banner from '@/components/banner/Banner.vue'
import Planos from '@/components/planos/Planos.vue'
import Modalidades from '@/components/modalidades/Modalidades.vue'
import Personal from '@/components/personal/Personal.vue'
import Grade from '@/components/grade/Grade.vue'
import Instalacao from '@/components/instalacao/Instalacao.vue'
import Whatsapp from '@/components/whatsapp/Whatsapp.vue'

export default {
  data() {
    return {}
  },
  components: {
    Banner,
    Planos,
    Modalidades,
    Personal,
    Grade,
    Instalacao,
    Whatsapp
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
