<template>
    <div class="menu-topo no-padding">
        <div class="container no-padding">
            <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 no-padding">
                <nav class="navbar navbar-default">
                    <div class="responsivo navbar-header hidden-lg hidden-md">
                        <a href="" class="btn hidden-md hidden-sm hidden-lg pull-left"
                            id="btn-hidden-pesquisa"><i class="fa fa-search" aria-hidden="true"></i></a>
                        <button type="button" class="navbar-toggle collapsed" data-toggle="collapse"
                            data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
                            <span class="sr-only">Toggle navigation</span>
                            <span class="icon-bar"></span>
                            <span class="icon-bar"></span>
                            <span class="icon-bar"></span>
                        </button>
                    </div>

                    <div class="collapse navbar-collapse no-padding" id="bs-example-navbar-collapse-1">
                        <ul class="nav navbar-nav menu-topo-nav">
                            <li class="dropdown hidden-xs hidden-sm">
                                <a href=""><i class="fa fa-home"></i></a>
                            </li>
                            <li class="dropdown">
                                <a href="#" class="dropdown-toggle acessibilidade" data-toggle="dropdown" role="button"
                                    aria-haspopup="true" aria-expanded="false">A Cidade</a>
                                <ul class="dropdown-menu">

                                    <li>
                                        <a class="acessibilidade" href="">
                                        </a>
                                    </li>
                                </ul>
                            </li>

                            <li class="dropdown">
                                <a href="#" class="dropdown-toggle acessibilidade" data-toggle="dropdown" role="button"
                                    aria-haspopup="true" aria-expanded="false">Secretarias</a>
                                <ul class="dropdown-menu">
                                    <li>
                                        <a class="acessibilidade" href="">
                                            </a>
                                    </li>
                                </ul>
                            </li>

                            <li class="dropdown">
                                <a href="#" class="dropdown-toggle acessibilidade" data-toggle="dropdown" role="button"
                                    aria-haspopup="true" aria-expanded="false">Ouvidoria</a>
                                <ul class="dropdown-menu">
                                    <li>
                                        <a class="acessibilidade" href="">Not&iacute;cias</a>
                                    </li>
                                </ul>
                            </li>

                            <li class="dropdown">
                                <a href="#" class="dropdown-toggle acessibilidade" data-toggle="dropdown" role="button"
                                    aria-haspopup="true" aria-expanded="false">Transpar&ecirc;ncia</a>
                                <ul class="dropdown-menu">
                                    <li>
                                        <a href="" target="_blank">Ouvidoria</a>
                                    </li>
                                </ul>
                            </li>

                            <li class="dropdown">
                                <a href="#" class="dropdown-toggle acessibilidade" data-toggle="dropdown" role="button"
                                    aria-haspopup="true" aria-expanded="false">Portal Geo Maring&aacute;</a>
                                <ul class="dropdown-menu">
                                    <li>
                                        <a class="acessibilidade" href="">Not&iacute;cias</a>
                                    </li>
                                </ul>
                            </li>
                        </ul>
                    </div>
                </nav>
            </div>
        </div>
    </div>
</template>

<style>
.menu-topo {
    background: #ffffff;
}

.menu-topo-nav {
    width: 100%;
    display: grid;
    grid-template-columns: 5.6% 17.6% 18.6% 18.6% 20.3% 19.3%;
    justify-items: stretch;
    align-items: center;
}

.menu-topo-nav::before {
    display: none;
}

ul>li>a>.fa {
    position: relative;
    left: 10%;
    bottom: 0px;
    font-size: 9px;
}

.col-lg-12 {
    width: 100%;
}

.navbar-nav>li {
    font-family: "Roboto", sans-serif;
    font: normal normal 900 14px/19px;
    font-weight: 900;
    letter-spacing: 0px;
}

.navbar {
    min-height: 55px;
    margin-bottom: 0px;
    border: 1px solid transparent;
    background: transparent;
    justify-content: center;
    white-space: nowrap;
}

.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
    border-color: #e7e7e7;
}

.navbar-default .navbar-nav>li>a {
    text-align: center;
    font: normal normal bold 17px/20px Montserrat;
    letter-spacing: 1.27px;
    color: #155c98;
    transition: 0.5s;
}

.fa-home:before {
    font-size: 20px;
}

.navbar-default .dropdown .navbar-nav>li>a:focus,
.navbar-default .navbar-nav>li>a:hover {
    color: #fff;
    background-color: #155c98;
    transition: 0.5s;
}

.nav-menu-responsivo .li-menu-responsivo:hover>.ul-submenu-responsivo .li-submenu {
    height: 30px;
    min-width: 260px;
}

.dropdown-menu>li>a:hover {
    color: #fff;
    text-decoration: none;
    background-color: #155c98;
}

.modalDialog:target {
    opacity: 1;
    pointer-events: auto;
    display: block;
}

.modalDialog>div {
    position: absolute;
    width: 87%;
    top: 50%;
    left: 8%;
}

#btn-hidden-pesquisa {
    font-size: 20px;
}

.busca {
    display: flex;
}

.overlay-content input {
    height: 66px;
    width: 85%;
    border: none;
    border-radius: 1rem 0rem 0rem 1rem;
    padding: 1rem;
    border: solid 4px #ffffff;
    font-size: 25px;
}

.overlay-content button {
    background: #008b30;
    border: none;
    color: #ffff;
    height: 66px;
    width: 19%;
    border-radius: 0rem 1rem 1rem 0rem;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 31px;
}

@media (max-width: 1024px) {
    .menu-topo-nav {
        display: flex;
        justify-content: space-between;
    }
}

@media (max-width: 912px) {
    .navbar-default .navbar-nav>li>a {
        font-size: 12px;
    }
}

@media (max-width: 600px) {
    .responsivo {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .navbar-default .navbar-toggle {
        border-color: #fff;
        background-color: #155c98;
    }

    .navbar-default .navbar-toggle .icon-bar {
        background-color: #fff;
    }

    .fa-search:before {
        color: #155c98;
    }

    .menu-topo-nav {
        flex-direction: column;
        align-items: center;
    }

    .navbar-default .navbar-nav .open .dropdown-menu>li>a {
        color: #fff;
        background-color: #155c98;
    }

    ul.dropdown-menu {
        color: #fff;
        text-align: center;
    }
}
</style>

<script>
export default {
    name: "MenuPrincipal",
};
</script>