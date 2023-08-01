<template>
  <Header />
  <RouterView />
  <Footer />
</template>

<script>
import Header from '@/common/header/Header.vue'
import Footer from '@/common/footer/Footer.vue'
import { RouterView } from 'vue-router'

export default {
  data() {
    return {}
  },
  components: {
    Header,
    Footer
  },
  computed: {
    
  },
  mounted() {
    
  },
  watch: {}
}
</script>

<style lang="scss">
@import '@/assets/scss/main.scss';
.v-enter-active,
.v-leave-active {
  transition: opacity 0.5s ease-in;
}

.v-enter-from,
.v-leave-to {
  opacity: 0;
}
</style>
