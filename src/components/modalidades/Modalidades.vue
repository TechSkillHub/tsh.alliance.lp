<template>
  <div id="modalidades">
    <div class="container text-center">
      <h1>Nossas Modalidades</h1>
    </div>

    <div class="container-fluid mt-4"></div>

    <div class="container boxes">
      <div class="row d-flex justify-content-between text-center">
        <div class="col-12 col-lg">
          <img src="./imgs/img1.webp" width="240" height="257" alt="" class="mb-4 img-fluid" />
          <h2>Kids 1</h2>
          <p class="px-4">
            Crianças podem praticar o Jiu-Jitsu a partir dos 04 anos de idade. As crianças aprendem
            dentro de um ambiente seguro e a aula é feita de forma lúdica e divertida.
          </p>
        </div>
        <div class="col-12 col-lg">
          <img src="./imgs/img2.webp" width="240" height="257" alt="" class="mb-4 img-fluid" />
          <h2>Kids 2</h2>
          <p class="px-4">
            Prática com crianças a partir dos 08 aos 14 anos de idade. As crianças aprendem dentro
            de um ambiente seguro e a aula é feita de forma objetiva e disciplinar.
          </p>
        </div>
        <div class="col-12 col-lg">
          <img src="./imgs/img3.webp" width="240" height="257" alt="" class="mb-4 img-fluid" />
          <h2>Iniciantes</h2>
          <p class="px-4">
            Método exclusivo da Alliance. O iniciante aprenderá nessa fase todos os fundamentos do
            Jiu-Jitsu. Nesse módulo não existe disputa propriamente dita.
          </p>
        </div>
        <div class="col-12 col-lg">
          <img src="./imgs/img4.webp" width="240" height="257" alt="" class="mb-4 img-fluid" />
          <h2>Intermediário</h2>
          <p class="px-4">
            Depois de passar pelo modo iniciante e aprender todas as técnicas e entender como
            funciona a luta o aluno passa a aprofundar seus conhecimentos e passa a treinar
            parcialmente.
          </p>
        </div>
        <div class="col-12 col-lg">
          <img src="./imgs/img5.webp" width="240" height="257" alt="" class="mb-4 img-fluid" />
          <h2>Avançado</h2>
          <p class="px-4">
            Nessa fase o aluno passa a receber conteúdo de alto nível de conhecimento, com técnicas
            variadas e atualizadas.
          </p>
        </div>
      </div>
      <a href="https://api.whatsapp.com/send?phone=5511944295818" target="_blank">
        <button class="primary mx-auto my-5">Matricule-se já</button>
      </a>
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
#modalidades {
  color: $grey-4;
  h1 {
    font-size: 50px;
    font-weight: 700;
  }
  h2 {
    font-size: 23px;
    font-weight: 700;
    letter-spacing: 0.1em;
  }
  p {
    line-height: 1.6em;
  }
  .container-fluid {
    background-color: $grey-4;
    height: 270px;
    @media (max-width: $xl) {
      height: 150px;
    }
  }
  .boxes {
    margin-top: -210px;
    @media (max-width: $xl) {
      margin-top: -110px;
    }
    img {
      width: 240px;
      height: auto;
    }
  }
}
</style>
