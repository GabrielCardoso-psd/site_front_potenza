<template>
<div class="background">
  <div class="container">
    <b-row>
    <img class="logo" src="../assets/img/car-icon-3657902_960_720.png" alt="">
      <div class="nav-bar nav">
        <div id="navbar-links">
          <div class="navbar-nav">
            <a class="nav-link" href="">Destaques da semana</a>
            <a class="nav-link" href="">Financiamento</a>
            <a class="nav-link" href="">Clientes</a>
            <a class="nav-link" href="">Simulação</a>
            <b-button>Faça sua ficha!</b-button>
          </div>
        </div>
      </div>
    </b-row>
  </div>
</div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
.logo{
  width: 150px;
}
</style>