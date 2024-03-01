<template>
  <div style="background: #f7f7f7; width: 100%; padding: 20px;">
    <div style="margin: 50px 0 30px 0">
      <h1 class="descricao-titulo">Agenda</h1>
      <div class="outline-titulo"></div>
    </div>

    <div class="bloco-agenda">
      <div class="agenda-item">
        <div class="data-item">
          <p style="margin: 10px">23<br /><b>04</b></p>
        </div>
        <div class="hora-item">
          <p><b>19:00</b>h</p>
        </div>
        <div class="descricao-item">
          <p>
            Nulla mattis velit id tortor posuere, hendrerit suscipit dui cursus.
          </p>
        </div>
      </div>

      <div class="agenda-item">
        <div class="data-item">
          <p style="margin: 10px">23<br /><b>04</b></p>
        </div>
        <div class="hora-item">
          <p><b>19:00</b>h</p>
        </div>
        <div class="descricao-item">
          <p>
            Nulla mattis velit id tortor posuere, hendrerit suscipit dui cursus.
          </p>
        </div>
      </div>

      <div class="agenda-item">
        <div class="data-item">
          <p style="margin: 10px">23<br /><b>04</b></p>
        </div>
        <div class="hora-item">
          <p><b>19:00</b>h</p>
        </div>
        <div class="descricao-item">
          <p>
            Nulla mattis velit id tortor posuere, hendrerit suscipit dui cursus.
          </p>
        </div>
      </div>

      <button class="btn-veja">VEJA <i class="fa fa-plus" aria-hidden="true"></i></button>
    </div>
  </div>
</template>

<style scoped>
.bloco-agenda {
    display: flex;
    flex-wrap: nowrap;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.agenda-item {
  display: flex;
  flex-direction: row;
  align-items: center;
  background: #fff;
  margin-top: 15px;
  margin-bottom: 20px;
}

.data-item {
  text-align: center;
  font: normal normal 300 31px Roboto;
  letter-spacing: 3.1px;
  color: #ffffff;
  opacity: 1;
  background: #155c98;
}

.hora-item {
  text-align: center;
  font: normal normal bold 18px Roboto;
  letter-spacing: 0px;
  color: #155c98;
  opacity: 1;
  border-right: 5px solid #155C98;
  padding: 15px;
}

.descricao-item {
  text-align: left;
  font: normal normal normal 16px Roboto;
  letter-spacing: 0px;
  color: #000000;
  opacity: 1;
  padding: 15px;
}

.btn-veja {
    background: #F7F7F7;
    width: 150px;
    border: 2px solid #155C98;
    border-radius: 30px;
    padding: 10px;
    color: #155C98;
    font: normal normal 600 14px Montserrat;
    transition: all ease 0.5s;
}

.btn-veja:hover {
  transform: scale(1.2);
  background-color: #155C98;
  color: #fff;
  transition: all ease 0.5s;
}
</style>

<script>
export default {
  name: "AgendaPrincipal",
};
</script>