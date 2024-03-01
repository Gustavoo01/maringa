<template>
  <div style="background: #f7f7f7">
    <div class="container" style="border-top: 1px solid #c1c1c1">
      <div style="margin-top: 50px">
        <h1 class="descricao-titulo">Aplicativos</h1>
        <div class="outline-titulo"></div>
      </div>
      <div class="bloco-aplicativos">
        <div class="item-aplicativo">
          <a href="">
            <img src="@/assets/images/ouvidoria.svg" alt="Ouvidoria" />
            <p class="titulo-aplicativo">OUVIDORIA</p>
            <p class="descricao-aplicativo">
              Nulla mattis velit id tortor posuere, hendrerit suscipit dui
              cursus.
            </p>
          </a>
        </div>
        <div class="item-aplicativo">
          <a href="">
            <img
              src="@/assets/images/estacione_legal.svg"
              alt="Estacione Legal"
            />
            <p class="titulo-aplicativo">ESTACIONE LEGAL</p>
            <p class="descricao-aplicativo">
              Nulla mattis velit id tortor posuere, hendrerit suscipit dui
              cursus.
            </p>
          </a>
        </div>
        <div class="item-aplicativo">
          <a href="">
            <img src="@/assets/images/petis.svg" alt="Petis" />
            <p class="titulo-aplicativo">PETIS</p>
            <p class="descricao-aplicativo">
              Nulla mattis velit id tortor posuere, hendrerit suscipit dui
              cursus.
            </p>
          </a>
        </div>
        <div class="item-aplicativo">
          <a href="">
            <img src="@/assets/images/flugo.svg" alt="Flugo" />
            <p class="titulo-aplicativo">FLUGO</p>
            <p class="descricao-aplicativo">
              Nulla mattis velit id tortor posuere, hendrerit suscipit dui
              cursus.
            </p>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
a {
  text-decoration: none;
}

img {
  transition: all ease 0.5s;
}

img:hover {
  transform: scale(1.1);
  transition: all ease 0.5s;
}

.bloco-aplicativos {
  display: flex;
  flex-wrap: nowrap;
  justify-content: space-between;
  margin: 50px 0 50px 0;
}

.item-aplicativo {
  text-align: center;
}

.titulo-aplicativo {
  text-align: center;
  font: normal normal 600 18px/22px Montserrat;
  letter-spacing: 0.9px;
  color: #000000;
  opacity: 1;
}

.descricao-aplicativo {
  text-align: center;
  font: normal normal normal 16px/24px Roboto;
  letter-spacing: 0px;
  color: #000000;
  opacity: 1;
  width: 200px;
}

@media (max-width: 912px) {
  .bloco-aplicativos {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    text-align: center;
    justify-items: center;
  }
}
</style>

<script>
export default {
  name: "AplicativosPrincipal",
};
</script>