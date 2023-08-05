<template>
  <div id="personal" class="container-fluid d-flex align-itens-center px-0 py-5">
    <div class="container d-flex flex-column justify-content-center text-center">
      <div class="row">
        <div class="col-12 d-flex justify-content-center">
          <div class="content">
            <div class="yellow">
              <img src="./imgs/img.webp" alt="Alliance" width="776" height="476" />
              <div class="grey">
                <h2>Aula Personal</h2>
                <p>
                  Você precisa de um horário mais flexível? Também temos nossa modalidade de Aulas
                  VIP.
                </p>
                <button class="primary mx-auto mt-4">Matricule-se já</button>
              </div>
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
#personal {
  .content {
    width: 930px;
    height: 660px;
    .yellow {
      width: 580px;
      height: 590px;
      background-color: $primary;
      position: relative;
      img {
        position: absolute;
        top: 50px;
        left: 70px;
      }
      .grey {
        position: absolute;
        bottom: -70px;
        right: -370px;
        width: 400px;
        height: 350px;
        background-color: $grey-4;
        text-align: center;
        padding: 40px;
        h2 {
          font-size: 34px;
          line-height: 1.6em;
          letter-spacing: 0.01em;
          color: $primary;
          font-weight: 700;
        }
        p {
          color: $white;
          font-size: 17px;
          line-height: 1.7em;
          max-width: 230px;
          margin: auto;
        }
      }
    }
  }
  @media (max-width: $lg) {
    .content {
      width: 100%;
      height: 560px;
      .yellow {
        width: 90%;
        height: 300px;
        img {
          width: 100%;
          height: auto;
          top: 20px;
          left: 30px;
        }
        .grey {
          width: 100%;
          height: auto;
          bottom: -270px;
          left: 20px;
          h2 {
            font-size: 36px;
          }
          button.primary {
            padding: 10px 50px;
          }
        }
      }
    }
  }
}
</style>
