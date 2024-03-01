<template>
  <div>
    <div class="float acessibilidade-bloco">
      <a href="">
        <i class="fa fa-wheelchair fa-2x" aria-hidden="true"></i>
      </a>
      <div class="acessibilidade-underline"></div>
      <a href="">
        <i class="fa fa-sign-language fa-2x" aria-hidden="true"></i>
      </a>
      <div class="acessibilidade-underline"></div>
      <a href=""
        ><p><b>A+ A-</b></p>
      </a>
      <div class="acessibilidade-underline"></div>
      <a href=""><i class="fa fa-adjust fa-2x" aria-hidden="true"></i></a>
    </div>
  </div>
</template>

<style scoped>
.float {
  position: fixed;
  width: 60px;
  height: 200px;
  top: 40px;
  right: 80px;
  background-color: #fff;
  color: #155c98;
  border-radius: 30px 2px 2px 30px;
  text-align: center;
  box-shadow: 2px 2px 3px #999;
}

.my-float {
  margin-top: 22px;
}

p {
  margin: 0%;
}

.acessibilidade-bloco {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  padding-right: 5px;
  opacity: 0.9;
}

.acessibilidade-underline {
  width: 50%;
  margin-left: auto;
  margin-right: auto;
  height: 2px;
  background: #c1c1c1;
}
</style>

<script>
export default {
  name: "AcessibilidadeButton",
};
</script>