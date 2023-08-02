<template>
  <div id="banner" class="container-fluid d-flex px-0">
    <div class="title d-flex flex-column justify-content-center text-center">
      <h1>ALLIANCE JIU-JITSU TATUAPÉ</h1>
      <h2>Melhore sua saúde física e a consciência corporal.</h2>
      <div class="arrow mx-auto">
        <svg
          preserveAspectRatio="none"
          data-bbox="20.002 20.002 159.995 159.995"
          viewBox="20.002 20.002 159.995 159.995"
          height="200"
          width="200"
          xmlns="http://www.w3.org/2000/svg"
          data-type="shape"
          role="presentation"
          aria-hidden="true"
        >
          <g>
            <path
              d="M140.119 20.002H59.881c-22.025 0-39.879 17.855-39.879 39.879v80.237c0 22.025 17.855 39.879 39.879 39.879h80.237c22.025 0 39.879-17.855 39.879-39.879V59.881c.001-22.024-17.854-39.879-39.878-39.879zm-17.451 79.135a4.997 4.997 0 0 1-7.07-.195L105.003 87.75v37.05c0 2.764-2.236 5-5 5s-5-2.236-5-5V87.746L84.397 98.942a4.972 4.972 0 0 1-3.628 1.562 4.97 4.97 0 0 1-3.437-1.372 4.993 4.993 0 0 1-.19-7.065L96.375 71.76a4.997 4.997 0 0 1 7.261 0l19.228 20.307a5.004 5.004 0 0 1-.196 7.07z"
            ></path>
          </g>
        </svg>
      </div>
    </div>
    <div class="col-md-4 px-0 d-none d-md-block">
      <img src="./imgs/img1.webp" alt="Alliance" class="w-100 h-100 img-fluid" />
    </div>
    <div class="col-md-4 col-12 px-0">
      <img src="./imgs/img2.webp" alt="Alliance" class="w-100 h-100 img-fluid" />
    </div>
    <div class="col-md-4 px-0 d-none d-md-block">
      <img src="./imgs/img3.webp" alt="Alliance" class="w-100 h-100 img-fluid" />
    </div>
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
#banner {
  color: $white;
  max-height: 706px;
  position: relative;
  .title {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: rgba(0, 0, 0, 0.1);
    h1 {
      font-size: 67px;
      font-weight: 900;
      @media (max-width: $lg) {
        font-size: 38px;
      }
    }
    h2 {
      font-size: 32px;
      font-weight: 300;
      @media (max-width: $lg) {
        font-size: 24px;
      }
    }
    .arrow {
      position: relative;
      @media (max-width: $lg) {
        width: 53px;
      }
      svg {
        position: absolute;
        top: 70px;
        fill-opacity: 0.72;
        height: 53px;
        width: 53px;
        fill: $primary;
        transform: rotate(180deg);
        @media (max-width: $lg) {
          top: 40px;
          left: 0;
        }
      }
    }
  }
}
</style>
