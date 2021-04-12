<template>
  <div>
    <div class="Postagem1">
      <div class="Textopostagem">
        <h1>Boletim Epidemiológico 385 - 05/04/2021</h1>
      </div>
      <div class="descricaopostagem">
        <div class="imgPostagem">
          <img src="../assets/img/34.png" height="100%" width="100%" alt="" />
        </div>
        <div class="texto2"></div>
      </div>
    </div>
  </div>
</template>

<style>
@import '../assets/css/estilo.css';
</style>

<script>
export default {
  data() {
    return {
      title: 'Boletim Epidemiológico 385 - 05/04/2021',
    }
  },
  head() {
    return {
      title: this.title,
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Boletim',
        },
      ],
    }
  },
}
</script>
