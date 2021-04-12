<template>
  <div>
    <div class="Postagem1">
      <div class="Textopostagem">
        <h1>Vacinação do povo de Taquaritinga</h1>
      </div>
      <div class="descricaopostagem">
        <div class="imgPostagem">
          <img src="../assets/img/11.jpeg" height="100%" width="100%" alt="" />
        </div>
        <div class="texto2">
          <p>
            A vacinação, decorrente da ordem cronológica estabelecida pelo
            Estado de São Paulo (SP) chegou hoje, no dia 3/25/2021. A idade
            requisitada para hoje era de 69 nove anos, descendo cada vez mais
            para chegar até a população mais jovem.
          </p>
        </div>
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
      title: 'Vacinação do povo de Taquaritinga',
    }
  },
  head() {
    return {
      title: this.title,
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Vacinação',
        },
      ],
    }
  },
}
</script>
