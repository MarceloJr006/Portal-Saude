<template>
  <div>
    <div class="carrossel">
      <b-carousel
        id="carousel-1"
        v-model="slide"
        :interval="6000"
        controls
        indicators
        background="#ababab"
        img-width="1024"
        img-height="380"
        style="text-shadow: 1px 1px 2px #333"
        @sliding-start="onSlideStart"
        @sliding-end="onSlideEnd"
      >
        <!-- Text slides with image -->

        <b-carousel-slide img-src="../assets/img/1.jpg">
          <h3>Dia Mundial da Saúde 2021: Saúde para todos</h3>
        </b-carousel-slide>
        <b-carousel-slide img-src="../assets/img/2.jpg">
          <h3>
            Butantan entrega mais 2,2 milhões de doses de vacina CoronaVac
          </h3>
        </b-carousel-slide>
        <b-carousel-slide img-src="../assets/img/3.jpeg">
          <h3>Taquaritinga começa a vacinação do COVID-19</h3>
        </b-carousel-slide>
      </b-carousel>
    </div>
    <br />
    <h1 class="evento">Covid-19</h1>
    <div class="cavaleiro">
      <div class="textocovid">
        <p>
          Os coronavírus são uma grande família de vírus comuns em muitas
          espécies diferentes de animais, incluindo camelos, gado, gatos e
          morcegos. Raramente, os coronavírus que infectam animais podem
          infectar pessoas, como exemplo do MERS-CoV e SARS-CoV. Recentemente,
          em dezembro de 2019, houve a transmissão de um novo coronavírus
          (SARS-CoV-2), o qual foi identificado em Wuhan na China e causou a
          COVID-19, sendo em seguida disseminada e transmitida pessoa a pessoa.
        </p>
      </div>
      <div class="imagembgs">
        <img src="../assets/img/covid.jpg" alt="" />
      </div>
    </div>
    <div class="container1">
      <div class="card1">
        <nuxt-link to="/noticia1">
          <img
            src="../assets/img/coronavac-1.jpg"
            alt=""
            height="350px"
            width="300px"
          />
          <p>
            A vacinação, decorrente da ordem cronológica estabelecida pelo
            Estado de ...
          </p>
        </nuxt-link>
      </div>
      <div class="card2">
        <nuxt-link to="/noticia2">
          <img
            src="../assets/img/roundel_stat3.png"
            alt=""
            height="350px"
            width="300px"
          />
          <p>
            Mesmo com a grande dificuldade na obtenção de vacinas contra a
            COVID-19 ...
          </p>
        </nuxt-link>
      </div>
      <div class="card3">
        <nuxt-link to="/noticia3">
          <img src="../assets/img/33.png" alt="" height="350px" width="300px" />
          <p>Boletim Epidemiológico 385 - 05/04/2021</p>
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<style>
@import '../assets/css/estilo.scss';
</style>
