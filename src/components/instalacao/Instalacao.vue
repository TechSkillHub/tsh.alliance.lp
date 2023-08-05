<template>
  <div id="instalacao" class="container-fluid">
    <h1 class="text-center">Nossas Instalações</h1>
    <div class="container-fluid py-5 bg">
      <div class="container d-flex flex-column justify-content-center text-center">
        <div class="row">
          <div class="col-12 d-flex">
            <div class="col">
              <img
                src="./imgs/img1.webp"
                alt="Alliance"
                width="506"
                height="716"
                class="img-fluid"
              />
            </div>
            <div class="col">
              <img
                src="./imgs/img2.webp"
                alt="Alliance"
                width="1013"
                height="716"
                class="img-fluid"
              />
            </div>
          </div>
          <div class="col-12 d-flex">
            <div class="col">
              <img
                src="./imgs/img3.webp"
                alt="Alliance"
                width="1013"
                height="716"
                class="img-fluid"
              />
            </div>
            <div class="col">
              <img
                src="./imgs/img4.webp"
                alt="Alliance"
                width="506"
                height="716"
                class="img-fluid"
              />
            </div>
          </div>
        </div>
      </div>
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
#instalacao {
  h1 {
    font-size: 50px;
    font-weight: 700;
    margin: 50px 0;
  }
  .bg {
    background-image: url('./imgs/bg.webp');
    background-position: top right;
    background-repeat: no-repeat;
  }
  .col {
    margin: 10px;
    img {
      cursor: pointer;
      transition: all ease-in 0.3s;
      &:hover {
        filter: brightness(0.8);
      }
    }
  }

  @media (max-width: $lg) {
    h1 {
      font-size: 36px;
      font-weight: 700;
      margin: 30px 0;
    }
    .col {
      margin: 5px;
    }
    .d-flex {
      flex-wrap: wrap;
      justify-content: center;
    }
  }
}
</style>
