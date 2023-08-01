<template>
  <div class="container-fluid d-flex align-itens-center px-0 py-5">
    <div class="container d-flex flex-column justify-content-center text-center">
      <div class="row">
        <div class="col-12">
          <h3>
            A Alliance Possui um método único de ensinamento, dividindo seus alunos por<br />
            grupos e níveis conforme seus objetivos e progresso no Jiu-Jitsu.
          </h3>
          <button class="primary mx-auto my-5">Matricule-se já</button>
        </div>
      </div>
      <div class="row">
        <div class="col-12 d-flex justify-content-center">
          <div class="content">
            <div class="yellow">
              <div class="grey">
                <h1>Nossos Planos</h1>
                <h3>Promoção por tempo limitado!</h3>
                <h2>Adulto somente no plano trimestral = R$ 200,00*</h2>
                <div class="table mt-3">
                  <div class="table-header">
                    <div>Mensal</div>
                    <div>Trimestral</div>
                    <div>Semestral</div>
                    <div>Anual</div>
                  </div>
                  <div class="table-info">
                    <div class="table-info-line f-55">
                      <div><span>R$</span> 240</div>
                      <div><span>R$</span> 220</div>
                      <div><span>R$</span> 210</div>
                      <div><span>R$</span> 195</div>
                    </div>
                    <div class="table-info-line f-25">
                      <div>Adulto</div>
                      <div>Adulto</div>
                      <div>Adulto</div>
                      <div>Adulto</div>
                    </div>
                    <div class="table-info-line f-55">
                      <div><span>R$</span> 190</div>
                      <div><span>R$</span> 170</div>
                      <div><span>R$</span> 160</div>
                      <div><span>R$</span> 150</div>
                    </div>
                    <div class="table-info-line f-25">
                      <div>Kids</div>
                      <div>Kids</div>
                      <div>Kids</div>
                      <div>Kids</div>
                    </div>
                  </div>
                </div>
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
#planos {
  h3 {
    font-size: 27px;
    line-height: 1.6em;
    letter-spacing: 0.01em;
    color: $grey-4;
    font-weight: 100;
    @media (max-width: $md) {
      font-size: 18px;;
    }
  }
  .content {
    width: 980px;
    height: 570px;
    .yellow {
      width: 580px;
      height: 500px;
      background-color: $primary;
      position: relative;
      .grey {
        position: absolute;
        top: 50px;
        left: 70px;
        width: 910px;
        height: 520px;
        background-color: $grey-4;
        text-align: left;
        padding: 40px;
        h1 {
          color: $primary;
          font-size: 45px;
          font-weight: 700;
        }
        h2 {
          color: $primary;
          font-size: 30px;
        }
        h3 {
          color: $white;
          font-size: 25px;
        }
        .table-header {
          font-size: 28px;
          font-weight: 700;
        }
        .table-info-line {
          &.f-25 {
            font-size: 25px;
          }
          &.f-55 {
            font-size: 55px;
          }
          >div span {
            font-size: 31px;
          }
        }
      }
    }
  }
  @media (max-width: $md) {
    .content {
      width: 100%;
      height: 560px;
      .yellow {
        width: 90%;
        height: 300px;
        .grey {
          width: 100%;
          height: auto;
          top: 30px;
          left: 20px;
          h1 {
            font-size: 38px;
          }
          h2 {
            font-size: 20px;
          }
          h3 {
            font-size: 18px;
          }
          .table-header,
          .table-info-line {
            width: 800px;
          }
        }
      }
    }
  }
}
</style>
