<template>
  <div class="fundo-servicos">
    <div class="conteudo-servicos container">
      <!-- <div>
        <h1 class="descricao-titulo">Serviços</h1>
        <div class="outline-titulo" style="width: 107px;"></div>
      </div> -->
      <div class="icones-titulo">
        <div class="faixa-titulo">
          <h1>Servi&ccedil;os</h1>
        </div>
      </div>
      <!-- <div class="box-geral-esquerda">
        <div class="icones-titulo1">
          <h1>Servi&ccedil;os</h1>
        </div>
      </div> -->

      <div class="acesso-rapido">
        <a href="https://www.lipsum.com/">
          <img src="@/assets/images/icone-servicos.svg" alt="Ouvidoria" />
          <p class="acessibilidade">Ouvidoria</p>
        </a>
        <a href="https://www.lipsum.com/">
          <img src="@/assets/images/icone-servicos.svg" alt="Ouvidoria" />
          <p class="acessibilidade">Ouvidoria</p>
        </a>
        <a href="https://www.lipsum.com/">
          <img src="@/assets/images/icone-servicos.svg" alt="Ouvidoria" />
          <p class="acessibilidade">Ouvidoria</p>
        </a>
        <a href="https://www.lipsum.com/">
          <img src="@/assets/images/icone-servicos.svg" alt="Ouvidoria" />
          <p class="acessibilidade">Ouvidoria</p>
        </a>
        <a href="https://www.lipsum.com/">
          <img src="@/assets/images/icone-servicos.svg" alt="Ouvidoria" />
          <p class="acessibilidade">Ouvidoria</p>
        </a>
        <a href="https://www.lipsum.com/">
          <img src="@/assets/images/icone-servicos.svg" alt="Ouvidoria" />
          <p class="acessibilidade">Ouvidoria</p>
        </a>
        <a href="https://www.lipsum.com/">
          <img src="@/assets/images/icone-servicos.svg" alt="Ouvidoria" />
          <p class="acessibilidade">Ouvidoria</p>
        </a>
        <a href="https://www.lipsum.com/">
          <img src="@/assets/images/icone-servicos.svg" alt="Ouvidoria" />
          <p class="acessibilidade">Ouvidoria</p>
        </a>
        <a href="https://www.lipsum.com/">
          <img src="@/assets/images/icone-servicos.svg" alt="Ouvidoria" />
          <p class="acessibilidade">Ouvidoria</p>
        </a>
        <a href="https://www.lipsum.com/">
          <img src="@/assets/images/icone-servicos.svg" alt="Ouvidoria" />
          <p class="acessibilidade">Ouvidoria</p>
        </a>
        <a href="https://www.lipsum.com/">
          <img src="@/assets/images/icone-servicos.svg" alt="Ouvidoria" />
          <p class="acessibilidade">Ouvidoria</p>
        </a>
        <a href="https://www.lipsum.com/">
          <img src="@/assets/images/icone-servicos.svg" alt="Ouvidoria" />
          <p class="acessibilidade">Ouvidoria</p>
        </a>
      </div>
      <div class="botao-mais-servicos col-xs-12 alinha-center">
        <a href="" class="acessibilidade">
          SERVIÇOS
          <i class="fa fa-plus" aria-hidden="true"></i>
        </a>
      </div>
    </div>
  </div>
</template>
  
<style>
.fundo-servicos {
  padding-top: 60px;
  background-color: #f7f7f7;
}

.icones-titulo {
  background-image: url("@/assets/images/fundo-icones.png");
  height: 116px;
  display: flex;
  align-items: center;
  mix-blend-mode: multiply;
}

div.faixa-titulo h1 {
  text-align: left;
  font: normal normal bold 28px/34px Roboto;
  letter-spacing: 0px;
  color: #666666;
  line-height: 42px;
  position: relative;
}

div.faixa-titulo h1::before {
  content: "";
  position: absolute;
  border-bottom: 5px solid #155c98;
  width: 100px;
  left: 0;
  bottom: 0;
  border-radius: 0px 0px 100px 0px;
}

.acesso-rapido {
  padding-top: 30px;
  display: grid;
  justify-items: center;
  grid-template-columns: repeat(6, 1fr);
  gap: 15px 10px;
}

.acesso-rapido a {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

  width: 175px;
  height: 120px;
  background: #e7e7e7 0% 0% no-repeat padding-box;
  gap: 11px;
  text-decoration: none;
  transition: all ease 0.5s;
}

.acesso-rapido a:hover {
  background-color: #5a565657;
  transform: scale(1.1);
  transition: all ease 0.5s;
}

.acesso-rapido a>p {
  text-align: center;
  font: normal normal 500 13px/15px Roboto;
  letter-spacing: 0px;
  color: #777777;
  margin: 0;
}

.botao-mais-servicos {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 40px 0 40px 0;
}

.botao-mais-servicos a {
  display: flex;
  flex-direction: row-reverse;
  justify-content: center;
  align-items: center;
  text-align: left;
  font: normal normal 800 15px/19px Montserrat;
  letter-spacing: 0px;
  color: #155a96;
  width: 200px;
  height: 56px;
  border: 2px solid #155c98;
  border-radius: 28px;
  text-decoration: none;
  gap: 5px;
  transition: all ease 0.5s;
}

.botao-mais-servicos a:hover {
  transform: scale(1.1);
  background-color: #155C98;
  color: #fff;
  transition: all ease 0.5s;
}

@media (max-width: 1280px) {
  .icones-titulo::after {
    left: 71px;
  }
}

@media (max-width: 1024px) {
  .icones-titulo::after {
    display: none;
  }

  .acesso-rapido {
    grid-template-columns: repeat(5, 1fr);
  }
}

@media (max-width: 912px) {
  .acesso-rapido {
    grid-template-columns: repeat(4, 1fr);
  }
}

@media (max-width: 600px) {
  .acesso-rapido {
    grid-template-columns: repeat(3, 1fr);
  }

  .acesso-rapido a {
    width: 165px;
  }
}

@media (max-width: 500px) {
  .acesso-rapido {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 300px) {
  .acesso-rapido {
    grid-template-columns: repeat(1, 1fr);
  }
}
</style>
  
<script>
export default {
  name: "AcessoRapido",
};
</script>