<template>
  <div>
    <nav id="header" class="navbar navbar-expand-md navbar-dark">
      <img src="./imgs/logo.webp" alt="Alliance" class="img-fluid m-auto" />
    </nav>
  </div>
</template>

<script>
export default {
  data() {
    return {}
  },
  mounted() {},
  methods: {
    hideMenu() {
      let el = document.getElementById('navbarCollapse')
      el.classList.remove('show')
    },
    openModal() {
      this.$store.commit('manager/SET_MODAL_DEFAULT', {
        show: true,
        title: 'Title Modal',
        body: 'Body Modal'
      })
    }
  },
  computed: {
    currentPage() {
      console.log(this.$store.state.manager.currentPage)
      return this.$store.state.manager.currentPage
    }
  },
  watch: {}
}
</script>

<style lang="scss" scoped></style>
