<template>
  <AcessibilidadeButton/>
  <TopoPrincipal />
  <MenuPrincipal />
  <AcessoRapido />
  <BannerPrincipal />
  <Noticias />
  <PodcastsAgenda/>
  <RedesSociais />
  <AplicativosPrincipal />
  <RodapePrincipal />
</template>

<script>
import TopoPrincipal from "../components/Topo.vue";
import MenuPrincipal from "../components/MenuPrincipal.vue";
import AcessoRapido from "../components/AcessoRapido.vue";
import BannerPrincipal from "../components/BannerPrincipal.vue";
import Noticias from "../components/NoticiasPrincipal.vue";
import PodcastsAgenda from "../components/PodcastsAgenda.vue";
import RedesSociais from "../components/RedesSociais.vue";
import AplicativosPrincipal from "../components/AplicativosPrincipal.vue";
import RodapePrincipal from "../components/Rodape.vue";
import AcessibilidadeButton from "../components/AcessibilidadeButton.vue";

export default {
  name: "Home",
  components: {
    TopoPrincipal,
    MenuPrincipal,
    AcessoRapido,
    BannerPrincipal,
    Noticias,
    PodcastsAgenda,
    RedesSociais,
    AplicativosPrincipal,
    RodapePrincipal,
    AcessibilidadeButton
  },
};
</script>

<style>
.descricao-titulo {
  text-align: left;
  font-family: Roboto;
  font-size: 28px;
  font-weight: 900;
  letter-spacing: 0px;
  color: #666666;
  opacity: 1;
  margin: 15px 0 5px 0;
}

.outline-titulo {
  width: 140px;
  height: 5px;
  background: #155c98;
  background-color: #155c98;
  border-radius: 0px 0px 100px 0px;
}
</style>