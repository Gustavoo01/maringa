<template>
    <div class="fundo-topo">
        <div class="container">
            <div class="topo-brasao">
                <div class="brasao-pref">
                    <a href="">
                        <img src="@/assets/images/logo-topo.png" alt="Bras&atilde;o do Munic&iacute;pio" />
                    </a>
                </div>
                <div class="icones-busca">
                    <div class="redes-socias-topo">
                        <a href="" target="_blank">
                            <img src="@/assets/images/informacao.svg" alt="Acesso" id="imagem1" />
                            <span>ACESSO A INFORMACAO</span>
                        </a>
                        <a href="" target="_blank">
                            <img src="@/assets/images/radar.svg" alt="Radar" id="imagem2" />
                            <span>RADAR DA TRANSPARENCIA</span>
                        </a>
                        <a href="" target="_blank">
                            <img src="@/assets/images/intranet.svg" alt="Intranet" id="imagem3" />
                            <span>PORTAL DO SERVIDOR/INTRANET</span>
                        </a>
                    </div>
                    <div id="divBusca" class="col-lg-10 col-md-10 hidden-xs">
                        <form name="buscanews"
                            action=""
                            method="POST" id="form-pesquisa" onSubmit="return validaBusca();">
                            <input type="text" id="txtBusca" class="acessibilidade form-control placeholder1" name="busca"
                                value="" title="Campo pesquisar" />
                            <button id="btnBusca" aria-label="Pesquisar">
                                <i class="fa fa-search"></i>
                            </button>
                        </form>
                    </div>
                    <div class="pesquisa hidden-lg hidden-md hidden-sm hidden-xs">
                        <a href="#openModal">
                            <i class="fa fa-search"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.fundo-topo {
  background-image: url('@/assets/images/fundo.svg');
  height: 153px;
}

.topo-brasao {
  display: flex;
  justify-content: space-between;
}

.brasao-pref {
  padding: 25px 0;
}

.brasao-pref img {
  width: 319px;
  height: 106px;
}

.icones-busca {
  display: flex;
  padding: 17px 0 38px 0;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-end;
}

.redes-socias-topo {
  display: flex;
  gap: 20px;
}

.redes-socias-topo a {
  display: flex;
  gap: 16px;
  align-items: center;

  text-decoration: none;
  text-align: left;
  font: normal normal normal 9px/21px Roboto;
  letter-spacing: 0.45px;
  color: #FFFFFF;
  transition: all 0.5s ease;
}

.redes-socias-topo a:hover {
  transition: all 0.5s ease;
  background-color: #13a64e;
  border-radius: 10px;
}


#divBusca {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: transparent;
  border: solid 1px #FFF;
  border-radius: 23px;
  width: 329px;
  height: 45px;
}

#form-pesquisa {
  display: flex;
}

#txtBusca {
  background-color: transparent;
  border: none;
  height: auto;
  width: 260px;
  outline: none;
  color: #FFF;
}

#btnBusca {
  background: transparent;
  border: none;
  height: auto;
  width: auto;
  font-size: 18px;
  color: #FFF;
}

@media (max-width: 912px) {
  .brasao-pref {
    padding: 50px 0 0 0;
  }

  .brasao-pref img {
    width: auto;
    height: 85px;
  }

  .icones-busca {
    gap: 42px;
  }

  .redes-socias-topo {
    gap: 10px;
  }


  .redes-socias-topo a {
    gap: 10px;
    font-size: 6px;
  }
}

@media (max-width: 600px) {
  .icones-busca {
    display: contents;
  }

  .redes-socias-topo {
    display: flex;
    gap: 20px;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
  }
}

@media (max-width: 430px) {
  .brasao-pref img {
    height: 65px;
  }

  .redes-socias-topo {
    gap: 10px;
    padding-top: 30px;
  }
}

@media (max-width: 400px) {
  .brasao-pref img {
    height: 55px;
  }
}

@media (max-width: 300px) {
  .fundo-topo {
    height: 173px;
  }

  .topo-brasao {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .brasao-pref {
    padding: 10px 0 0 0;
  }

  .redes-socias-topo {
    padding-top: 10px;
  }
}
</style>

<script>
export default {
    name: "TopoPrincipal",
};
</script>