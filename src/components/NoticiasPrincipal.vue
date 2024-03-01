
<template>
    <div class="fundo-noticias">
        <div class="container">
            <div class="noticias">
                <div style="margin: 50px 0 30px 0">
                    <h1 class="descricao-titulo">Notícias</h1>
                    <div class="outline-titulo" style="width: 103px;"></div>
                </div>
                <div class="noticias-lista">
                    <div class="noticias-destaque col-lg-8 col-md-8">
                        <div id="noticia-destaque-carousel" class="carousel slide" data-ride="carousel">
                            <ol class="carousel-indicators">
                                <li data-target="#noticia-destaque-carousel" data-slide-to="" class="active"></li>
                            </ol>
                            <div class="carousel-inner">
                                <div class="item active" id="noticia-destaque">
                                    <a href="">
                                        <figure>
                                            <img class="item-destaque" src="@/assets/images/noticia-destaque.png"
                                                alt="foto destaque">
                                            <figcaption>
                                                <p class="texto-destaque acessibilidade">
                                                    Prefeitura segue com inscrições abertas até 30 de junho para cursos
                                                    profissionalizantes gratuitos
                                                </p>
                                            </figcaption>
                                        </figure>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="ultimas-noticias col-lg-4 col-md-4">
                        <div class="item-ultimas">
                            <div class="conteudo-ultimas">
                                <a href="">
                                    <img src="@/assets/images/noticia-ultimas.png" alt="">
                                    <figcaption class="acessibilidade">
                                        Empresas interessadas na PPP da iluminação pública devem apresentar documentação em
                                        9 de
                                        maio na Bolsa e Valores de SP; licitação será em 23 de maio
                                    </figcaption>
                                </a>
                            </div>
                        </div>
                        <div class="item-ultimas">
                            <div class="conteudo-ultimas">
                                <a href="">
                                    <img src="@/assets/images/noticia-ultimas.png" alt="">
                                    <figcaption class="acessibilidade">
                                        Protocolo de segurança da rede municipal é atualizado e colocado em funcionamento
                                    </figcaption>
                                </a>
                            </div>
                        </div>
                        <div class="item-ultimas">
                            <div class="conteudo-ultimas">
                                <a href="">
                                    <img src="@/assets/images/noticia-ultimas.png" alt="">
                                    <figcaption class="acessibilidade">
                                        Agência do Trabalhador de Maringá inicia semana com OFERTA de 460 empregos
                                    </figcaption>
                                </a>
                            </div>
                        </div>
                        <div class="item-ultimas">
                            <div class="conteudo-ultimas">
                                <a href="">
                                    <img src="@/assets/images/noticia-ultimas.png" alt="">
                                    <figcaption class="acessibilidade">
                                        Referência em políticas de habitação social, Prefeitura conquista premiação nacional
                                        com
                                        ProZeis
                                    </figcaption>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="botao-mais-noticias col-xs-12 alinha-center">
                    <a href="" class="acessibilidade">
                        NOTÍCIAS
                        <i class="fa fa-plus" aria-hidden="true"></i>
                    </a>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.fundo-noticias {
    background-color: #F7F7F7;
}

.noticias-destaque,
.ultimas-noticias {
    padding: 0;
}

.carousel-indicators {
    top: 94%;
}

.carousel-indicators {
    opacity: 0.77;
}

#noticia-destaque {
    width: 720px;
    height: 480px;
}

#noticia-destaque figcaption {
    position: absolute;
    bottom: 0%;
    background: transparent linear-gradient(180deg, #00000000 0%, #030303A6 56%, #040404 100%) 0% 0% no-repeat padding-box;
    width: 100%;
    height: 135px;
    padding: 0 50px;
}

.texto-destaque {
    text-align: left;
    font: normal normal bold 28px/40px Roboto;
    letter-spacing: 0px;
    color: #FFFFFF;
}

.ultimas-noticias {
    display: flex;
    flex-direction: column;
    gap: 18px;
}

.item-ultimas {
    background-color: #E7E7E7;
}

.conteudo-ultimas>a {
    display: flex;
    gap: 15px;
    height: 106px;
    align-items: center;
    padding: 11px;
}

.conteudo-ultimas>a>img {
    widows: 128px;
    height: 85px;
}

.conteudo-ultimas>a>figcaption {
    text-align: left;
    font: normal normal normal 12px/18px Roboto;
    letter-spacing: 0px;
    color: #000000;
}

.botao-mais-noticias {
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 40px 0 40px 0;
}

.botao-mais-noticias a {
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

.botao-mais-noticias a:hover {
    transform: scale(1.1);
    background-color: #155C98;
    color: #fff;
    transition: all ease 0.5s;
}

@media (max-width: 912px) {
    #noticia-destaque>a>figure>img{
        width: 100%;
        height: 100%;
    }
    .ultimas-noticias {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        gap: 15px;
    }
}

@media (max-width: 540px) {
    #noticia-destaque {
        width: 100%;
        height: 211px;
    }

    #noticia-destaque>a>figure>figcaption {
        height: 90px;
    }

    .texto-destaque {
        font-size: 20px;
        line-height: 22px;
    }

    .ultimas-noticias {
        display: flex;
    }
}
</style>

<script>
export default {
    name: "Noticias",
};
</script>