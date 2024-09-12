<template>
  <div class="container">
    <div class="header">
      <p>Autora:
        <b>"Alba Riera"</b>
      </p>
      <h1 class="title">Juego de Memoria</h1><br />
    </div>
    <div class="menu">
      <ol>
        <li>Nivel 1</li>
        <li>Nivel 2</li>
        <li>Nivel 3</li>
        <li>Nivel 4</li>
      </ol>

    </div>
    <div class="main">

    </div>
    <div class="footer">
      <p>Este juego ha sido creado para una prueba práctica de un modulo en programación.<br/> Ruego nos hagan llegar sus mejoras a <a>webriera@gmail.com</a></p>



    </div>
  </div>
</template>

<script setup>

</script>

<style>
.container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  gap: 5px;
}

.header {

  width: auto;
  text-align: center;

}

.menu {
 width: 20%;
 text-align:center;

}

.footer {
  flex-direction: row-reverse;
  height: 20%;
  width: 100%;
  background-color: rgb(0, 170, 255);
}

.main {

  width: auto;
  background-color: azure;
}

.title {
  color: rgb(0, 170, 255);



}
</style>
