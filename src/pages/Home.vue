<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <div class="jumbotron">
    <header>
      <!-- Background image -->
      <div class="p-5 text-center bg-image" style="">
        <div class="mask" style="background-color: rgba(0, 0, 0, 0.6)">
          <div class="d-flex justify-content-center align-items-center h-100">
            <div class="text-white">
              <h1 class="display-4">Bienvenue sur Mon Portfolio mon Reuf</h1>
            </div>
          </div>
        </div>
      </div>
      <!-- Background image -->
    </header>
    <div class="container">
      <p class="lead">
        Ici, vous découvrirez mon monde artistique, un lieu où la créativité
        s'épanouit. À travers mes projets, je vous invite à explorer ma passion
        pour l'art, la photographie, le design et bien plus encore. Chaque œuvre
        raconte une histoire, chaque pixel est imprégné de mon engagement envers
        l'expression artistique. Je vous invite à parcourir ces pages, à vous
        laisser inspirer, et à partager ce voyage avec moi. Bienvenue à bord !
      </p>
      <h2>Projets</h2>
      <img
        src="../../public/img/examen-logo.svg"
        class="rounded float-start"
        alt="Logo1"
        width="200"
        height="200"
      />
      <img
        src="../../public/img/Logo.svg"
        class="rounded float-end"
        alt="Logo2"
        width="200"
        height="200"
      />

      <RouterLink
        to="/projets"
        class="btn btn-primary btn-lg mt-3 d-block mx-auto"
      >
        Voir tous les projets
      </RouterLink>
    </div>
  </div>
</template>
