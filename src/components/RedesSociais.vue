<template>
    <div style="background: #f7f7f7">
        <div class="container">
            <div class="redes">
                <a href="">
                    <div class="rede-social">
                        <img class="rede-icon" src="@/assets/images/instagram.svg" alt="Instagram" />
                        <p class="titulo-rede">INSTAGRAM</p>
                    </div>
                </a>
                <a href="">
                    <div class="rede-social">
                        <img class="rede-icon" src="@/assets/images/youtube.svg" alt="Youtube" />
                        <p class="titulo-rede">YOUTUBE</p>
                    </div>
                </a>
                <a href="">
                    <div class="rede-social">
                        <img class="rede-icon" src="@/assets/images/spotify.svg" alt="Spotify" />
                        <p class="titulo-rede">SPOTIFY</p>
                    </div>
                </a>
                <a href="">
                    <div class="rede-social">
                        <img class="rede-icon" src="@/assets/images/linkedin.svg" alt="Linkedin" />
                        <p class="titulo-rede">LINKEDIN</p>
                    </div>
                </a>
            </div>
        </div>
    </div>
</template>

<style>
.rede-social {
    display: flex;
    margin: 20px;
}

.titulo-rede {
    align-self: center;
    margin-bottom: 0;
    text-align: left;
    font: normal normal normal 18px/22px Roboto;
    letter-spacing: 1.8px;
    color: #000000;
    text-transform: uppercase;
    opacity: 1;
    font-size: 18px;
    padding: 10px;
    margin-left: 20px;
}

.redes {
    display: flex;
    flex-wrap: nowrap;
    justify-content: space-between;
}

a {
    text-decoration: none;
}

.icon-button {
    width: 64px;
    height: 64px;
    border-radius: 3.6rem;
    background: #3b5998;
}

/* Circle */
.icon-button span {
    background-color: aquamarine;
    border-radius: 0;
    display: block;
    height: 0;
    position: absolute;
    -webkit-transition: all 0.3s;
    -moz-transition: all 0.3s;
    -o-transition: all 0.3s;
    transition: all 0.3s;
    width: 0;
}

.icon-button:hover span {
    width: 64px;
    height: 64px;
    border-radius: 3.6rem;
}

.icon-rede {
    color: #fff;
}

.icon-rede span {
    background-color: #c7d0e6;
}

@media (max-width: 912px) {
    .redes {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
    }
}
</style>

<script>
export default {
    name: "RedesSociais",
};
</script>
