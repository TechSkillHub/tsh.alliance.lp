<template>
  <div class="mask" @click="close()">
    <div id="modalDefault" class="modal d-block show">
      <div class="modal-dialog modal-dialog-centered">
        <div class="modal-content">
          <div class="modal-header">
            <h1 class="modal-title fs-5">{{ modalInfo.title }}</h1>
            <button type="button" class="btn-close" @click="close()"></button>
          </div>
          <div class="modal-body">
            {{ modalInfo.body }}
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-secondary" @click="close()">Close</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props: {
    modalInfo: {
      type: Object
    }
  },
  data() {
    return {}
  },
  mounted() {
    document.body.classList.add('scroll-hidden')
  },
  unmounted() {
    setTimeout(() => {
      document.body.classList.remove('scroll-hidden')
    }, 500)
  },
  created() {},
  methods: {
    close() {
      this.$store.commit('manager/SET_MODAL_DEFAULT', { show: false })
    }
  }
}
</script>
<style lang="scss" scoped>
.mask {
  display: flex;
}
</style>
