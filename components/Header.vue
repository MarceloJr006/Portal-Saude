<template>
  <div>
    <div class="grid">
      <div class="logo">
        <nuxt-link to="/">
          <img
            class="logo"
            src="http://www.taquaritinga.sp.gov.br/Content/img/brasao.png"
            alt="Logo da IGN"
            height="90em"
            width="70em"
          />
        </nuxt-link>
      </div>
      <div class="sony">
        <nuxt-link to="/sony">Farmacia</nuxt-link>
      </div>
      <div class="microsoft">
        <nuxt-link to="/microsoft">Hospitais</nuxt-link>
      </div>
      <div class="nintendo">
        <nuxt-link to="/nintendo">Sobre</nuxt-link>
      </div>
      <div class="blog">
        <a href="#" target="_blank">Blog</a>
      </div>
      <div>
        Login:<br /><input id="login" type="text" name="login" /><br />
        Senha:<input id="senha" type="password" name="senha" /><br />
        <input id="cadastrar" type="submit" value="Login" name="Login" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
}

// <?php

// $login = $_POST['login'];
// $senha = MD5($_POST['senha']);
// $connect = mysql_connect('nome_do_servidor','nome_de_usuario','senha');
// $db = mysql_select_db('nome_do_banco_de_dados');
// $query_select = "SELECT login FROM usuarios WHERE login = '$login'";
// $select = mysql_query($query_select,$connect);

//   if($login == "" || $login == null){
//     alert('O campo login deve ser preenchido');window.location.href='index.vue'
//   }
</script>

<style>
@import '../assets/css/estilo.scss';
</style>
