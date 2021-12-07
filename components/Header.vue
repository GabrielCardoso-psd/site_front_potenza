<template>
  <div>
    <div class="background">
      <div class="container">
        <div>
          <img class="img" src="../assets/img/car-icon-3657902_960_720.png" alt="">
        </div>
        <div id="navbar-links">
          <div class="navbar-nav">
            <a class="nav-link" href="#camuflagem">Destaques da semana</a>
            <a class="nav-link" href="#procedimentos">Financiamento</a>
            <a class="nav-link" href="#contato">Clientes</a>
            <a class="nav-link" href="#contato">Simulação</a>
            <a href="" target="_blank"><b-button class="botao"><span class="icones fa-lg"><font-awesome-icon :icon="['fab', 'whatsapp']"/></span>Faça sua ficha!</b-button></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
.background{
  background-color: black;
  padding-bottom: 15px;
  padding-top: 15px;
}

.img{
  width: 15%;
  padding: 15px;
}

.nav-link{
  color: white;
  text-decoration: none;
  font-family: ;
}
</style>