<template>
    <div>
      <div class="container">
        <div class="horario-atendimento">
          HOR&Aacute;RIO DE ATENDIMENTO: SEGUNDA A SEXTA DAS 08H &Aacute;S 11:30H
          E DAS 13H &Aacute;S 17:30H
        </div>
      </div>
  
      <div style="background: #145d99">
        <div class="container">
          <div class="dados-rodape">
            <img
              src="@/assets/images/sei.png"
              alt="SEI - Sistema Eletr&ocirc;nico de Informa&ccedil;&otilde;es"
              style="height: 110px"
            />
            <div class="centro-rodape">
              <div class="logo-rodape">
                <img
                  src="@/assets/images/logo-topo.png"
                  alt="Prefeitura Municial de Maring&aacute;"
                  style="width: 230px; height: 75px"
                />
              </div>
              <div>
                <p class="endereco">
                  AV. XV DE NOVEMBRO, 701 - CEP 87013-230 - CENTRO -
                  MARING&Aacute;
                </p>
                <p class="telefone"><b>(44) 3221-1234</b></p>
              </div>
            </div>
            <img
              src="@/assets/images/prevencao-corrupcao.png"
              alt="Programa Nacional de Combate a Corrup&ccedil;&atilde;o"
              style="height: 110px"
            />
          </div>
  
          <hr style="color: #ffffff; opacity: 1" />
  
          <div class="atualizacao-rodape">
            <div class="mapa-site">
              <div>
                <img
                  src="@/assets/images/mapa-site.svg"
                  alt="Mapa do Site"
                />
              </div>
              <div style="margin: 7px 0 0 5px">
                <p>MAPA DO SITE</p>
              </div>
            </div>
  
            <div class="dados-atualizacao">
              <p>&Uacute;ltima atualiza&ccedil;&atilde;o do site:</p>
            </div>
  
            <div>
              <img
                src="@/assets/images/logo-inga.svg"
                alt="Ing&aacute; Digital"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <style>
  .horario-atendimento {
      text-align: center;
      font: normal normal bold 11px/21px Roboto;
      letter-spacing: 2.2px;
      color: #145C98;
      opacity: 1;
      padding: 20px;
      font-weight: 900;
  }
  
  .dados-rodape {
      display: flex;
      justify-content: space-between;
      padding-top: 20px;
  }
  
  .logo-rodape {
      display: flex;
      justify-content: center;
      margin-bottom: 10px;
  }
  
  .endereco {
      text-align: center;
      font: normal normal normal 12px Roboto;
      letter-spacing: 1.65px;
      color: #FFFFFF;
      margin-bottom: 0;
  }
  
  .telefone {
      font-size: 12px;
      text-align: center;
      font: bold 900 12px/21px Roboto;
      letter-spacing: 2.4px;
      color: #FFFFFF;
      opacity: 1;
      margin-bottom: 0;
  }
  
  .atualizacao-rodape {
      display: flex;
      justify-content: space-between;
      color: #FFFFFF;
      margin-bottom: 15px;
  }
  
  .mapa-site {
      display: flex;
      flex-wrap: nowrap;
      white-space: nowrap;
      text-align: left;
      font: normal normal normal 13px/15px Roboto;
      letter-spacing: 1.95px;
      color: #FFFFFF;
      opacity: 1;
  }
  
  .dados-atualizacao {
      text-align: center;
      font: normal normal normal 12px/21px Roboto;
      letter-spacing: 0px;
      color: #FFFFFF;
      opacity: 1;
  }
  </style>
  
  <script>
  export default {
      name: 'RodapePrincipal'
  }
  </script>