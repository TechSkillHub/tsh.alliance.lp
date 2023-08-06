<template>
  <div id="whatsapp">
    <a href="https://api.whatsapp.com/send?phone=5511944295818" target="_blank">
      <img src="./imgs/whatsapp.webp" alt="Alliance" width="80" height="76" class="img-fluid" />
    </a>
  </div>
</template>

<script>
export default {
  data() {
    return {}
  },
  methods: {}
}
</script>

<style lang="scss" scoped>
#whatsapp {
  position: fixed;
  right: 5%;
  bottom: 5%;
  @media (max-width: $lg) {
  }
}
</style>
