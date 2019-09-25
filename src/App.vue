<template>
  <div id="app">
    <header class="header">
      <div class="navigation">
        <div class="navigation__superior">
          <i class="fas fa-bars navigation__icon"></i>
          <img  class="navigation__logo" src="./assets/images/logo.png" alt="Logo">
          <h3 class="navigation__title">
            <span class="navigation__text">Ingeniería de Sistemas</span>
            <span class="navigation__text">e Informática</span>
          </h3>
          
        </div>
        <nav class="navigation__menu">
          <a class="navigation__link active" href="#">Inicio</a>
          <a class="navigation__link" href="#">Nosotros</a>
          <a class="navigation__link" href="#">Proyectos</a>
          <a class="navigation__link" href="#">Eventos</a>
          <a class="navigation__link" href="#">Laboratorios</a>
          <a class="navigation__link" href="#">Noticias</a>
          <a class="navigation__link" href="#">Docentes</a>
        </nav>
      </div>
    </header>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="scss">
@import "./assets/sass/main.scss";
</style>
