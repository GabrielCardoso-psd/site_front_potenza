<template>
  <div>
    <div class="background">
      <div class="container">
        <b-row>
        <img class="logo" src="../assets/img/car-icon-3657902_960_720.png" alt="">

        <div id="navbar-links">
          <div class="navbar-nav">
            <a class="nav-link" href="">Destaques da semana</a>
            <a class="nav-link" href="">Financiamento</a>
            <a class="nav-link" href="">Clientes</a>
            <a class="nav-link" href="">Simulação</a>
            <a class="botao" href=""><b-button class="botao">Faça sua ficha!</b-button></a>
          </div>
        </div>
        </b-row>
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
  padding-top: 15px;
  padding-bottom: 15px;
}

.logo{
  width: 150px;
}

.nav-link{
  color: white;
  text-decoration: none;
  font-family: Montserrat, sans-serif;
  font-size: 5px;
}

.botao{
  color: white;
  font-family: Montserrat, sans-serif;
  background-color: #ff6000;
  border: none;
  text-decoration: none;
  padding: 10px 10px 10px 10px;
  border-radius: 5px;
}
</style>