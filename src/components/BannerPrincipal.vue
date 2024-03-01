<template>
  <div class="fundo-banner">
    <div class="container">
      <div class="row">
        <div id="banner-carousel" class="carousel slide" data-ride="carousel">
          <ol class="carousel-indicators">
            <li data-target="#banner-carousel" data-slide-to="" class="active"></li>
          </ol>
          <div class="carousel-inner">
            <div class="item active" id="banner">
              <a href="">
                <img src="@/assets/images/banner.jpg" title="Banner Pontal do Paran&aacute;" class="img-responsive banner"
                  alt="" />
              </a>
            </div>
          </div>
        </div>
      </div>
      <div class="carousel-button-slider controle-carrossel hidden-xs">
        <a class="left-slider" href="#banner-carousel" data-slide="prev">
          <i class="fa fa-chevron-left" aria-hidden="true"></i>
        </a>
        <a class="right-slider" href="#banner-carousel" data-slide="next">
          <i class="fa fa-chevron-right" aria-hidden="true"></i>
        </a>
      </div>
    </div>
  </div>
</template>
  
<style>
.fundo-banner {
  padding: 30px 0 30px 0;
}

.item a {
  text-align: -webkit-center;
}

.item>a>img {
  width: 100%;
  height: 351px !important;
  object-fit: fill;
}

.carousel-indicators {
  top: 76%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.carousel-indicators li {
  width: 10px !important;
  height: 10px !important;
  background-color: white;
  margin: 25px;
  transition: all ease 0.5s;
}

.carousel-indicators .active {
  width: 16px !important;
  height: 16px !important;
  border: 4px solid white;
  background-color: rgba(0, 255, 255, 0);
  margin: 25px;
  transition: all ease 0.5s;
}

.carousel-button-slider {
  position: relative;
  bottom: 190px;
  display: flex;
  justify-content: space-between;
}

.carousel-button-slider a:hover {
  text-decoration: none;
  background-color: #5a565657;
  transition: all ease 0.5s;
}

.carousel-button-slider a:focus {
  text-decoration: none;
}

.left-slider {
  display: flex;
  width: 50px;
  height: 50px;
  background: #ffffff 0% 0% no-repeat padding-box;
  box-shadow: 0px 0px 10px #00000029;
  align-items: center;
  justify-content: center;
  position: relative;
  right: 11%;
  border-radius: 50%;
  transition: all ease 0.5s;
}

.right-slider {
  display: flex;
  width: 50px;
  height: 50px;
  background: #ffffff 0% 0% no-repeat padding-box;
  box-shadow: 0px 0px 10px #00000029;
  align-items: center;
  justify-content: center;
  position: relative;
  left: 11%;
  border-radius: 50%;
  transition: all ease 0.5s;
}

.left-slider,
.right-slider i {
  font-size: 20px;
  color: #000;
}

@media (max-width: 1280px) {
  .carousel-button-slider a:hover {
    background-color: #fff;
  }

  .left-slider,
  .right-slider {
    right: 0;
    left: 0;
  }
}

@media (max-width: 600px) {
  .item>a>img {
    width: 90%;
    height: auto !important;
  }
}
</style>
  
<script>
export default {
  name: "BannerPrincipal",
};
</script>