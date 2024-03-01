<template>
  <div style="background: #000; padding: 20px;">
    <div style="margin: 50px 0 30px 0">
      <h1 class="descricao-titulo">Podcasts</h1>
      <div class="outline-titulo"></div>
    </div>
    <div class="bloco-podcast">
      <div class="item-podcast">
        <img class="img-podcast" src="@/assets/images/img-podcast.png" alt="" />
        <p class="descricao-podcast">
          Nulla mattis velit id tortor posuere, hendrerit suscipit dui cursus.
          Nullam viverra ligula sed diam pretium viverra.
        </p>
      </div>

      <div class="item-podcast">
        <img class="img-podcast" src="@/assets/images/img-podcast.png" alt="" />
        <p class="descricao-podcast">
          Nulla mattis velit id tortor posuere, hendrerit suscipit dui cursus.
          Nullam viverra ligula sed diam pretium viverra.
        </p>
      </div>

      <div class="item-podcast">
        <img class="img-podcast" src="@/assets/images/img-podcast.png" alt="" />
        <p class="descricao-podcast">
          Nulla mattis velit id tortor posuere, hendrerit suscipit dui cursus.
          Nullam viverra ligula sed diam pretium viverra.
        </p>
      </div>

      <button class="btn-videos"><i class="fa fa-plus" aria-hidden="true"></i> <b>VÍDEOS</b></button>
    </div>
  </div>
</template>

<style scoped>
.bloco-podcast {
  display: flex;
  flex-wrap: nowrap;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.item-podcast {
  display: flex;
}

.descricao-titulo {
  color: #ffffff;
}

.img-podcast {
  margin: 30px 15px 30px 0px;
  width: 120px;
  height: 70px;
}

.descricao-podcast {
  text-align: left;
  font: normal normal normal 15px/20px Roboto;
  letter-spacing: 0px;
  color: #ffffff;
  opacity: 1;
  width: 350px;
  margin: 30px 30px 0 0;
}

.btn-videos {
  background: #000;
  width: 150px;
  border: 2px solid #fff;
  border-radius: 30px;
  padding: 10px;
  color: #fff;
  font: normal normal 600 14px Montserrat;
  transition: all ease 0.5s;
}

.btn-videos:hover {
  transform: scale(1.2);
  background-color: #fff;
  color: #000;
  transition: all ease 0.5s;
}

@media (max-width: 1024px) {
  .descricao-podcast {
    width: 260px;
  }
}
</style>

<script>
export default {
  name: "PodcastsPrincipal",
};
</script>