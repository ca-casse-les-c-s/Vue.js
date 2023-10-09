<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
  <div class="jumbotron">
    <div class="container">
      <h1 class="display-4">Bienvenue sur Mon Portfolio mon Reuf </h1>
      <p class="lead">
        Ici, vous découvrirez mon monde artistique, un lieu où la créativité s'épanouit. À travers mes projets, je vous
        invite à explorer ma passion pour l'art, la photographie, le design et bien plus encore. Chaque œuvre raconte une
        histoire, chaque pixel est imprégné de mon engagement envers l'expression artistique. Je vous invite à parcourir
        ces pages, à vous laisser inspirer, et à partager ce voyage avec moi.

        Bienvenue à bord !
      </p>
      <h2>Projets</h2>
      <img src="../../public/img/examen-logo.svg" class="rounded float-start" alt="Logo1" width="200" height="200">
      <img src="../../public/img/Logo.svg" class="rounded float-end" alt="Logo2" width="200" height="200">
      <RouterLink to="/projets" class="btn btn-primary btn-lg">Voir tous les projets</RouterLink>
    </div>
  </div>
</template>
