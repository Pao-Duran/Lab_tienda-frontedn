<script setup lang="ts">
import { useRoute } from "vue-router";
const location = useRoute();
</script>
<template>
  <header>
    <nav
     class="navbar navbar-expand-lg fixed-top" :style="location.path != '/' ? 'background-color: black ' : ''">
  <!-- Contenido de la barra de navegación -->

    <div class="container">
      <RouterLink to="/" class="navbar-brand"> Cosmetics  </RouterLink>

      <a href="ticket.html" class="btn custom-btn d-lg-none ms-auto me-5"
        >Iniciar Sesión</a
      >
<br>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarNav">
         <ul class="navbar-nav align-items-lg-center ms-auto me-lg-5"> 
          <li class="nav-item">
            <RouterLink to="/" class="nav-link click-scroll">Inicio</RouterLink> 
          </li>

          <li class="nav-item">
            <RouterLink to="/about" class="nav-link click-scroll"
              >Acerca De</RouterLink
            >
          </li>

          <li class="nav-item">
            <RouterLink to="/productos" class="nav-link click-scroll"
              >Productos</RouterLink
            >
          </li>
          <li class="nav-item">
            <RouterLink to="/personas" class="nav-link click-scroll"
              >Cliente</RouterLink
            >
          </li>
          <li class="nav-item">
            <RouterLink to="/categorias" class="nav-link click-scroll"
              >Categoria</RouterLink
            >
          </li>
          <li class="nav-item">
            <RouterLink to="/ventas" class="nav-link click-scroll"
              >Venta</RouterLink
            >
          </li>
          <li class="nav-item">
            <RouterLink to="/usuarios" class="nav-link click-scroll"
              >Usuario</RouterLink
            >
          </li>
          <li class="nav-item">
            <RouterLink to="/salir" class="nav-link click-scroll"
              >Salir</RouterLink
            >
          </li>
        </ul>

        <a href="ticket.html" class="btn custom-btn d-lg-block d-none"
          >Iniciar Sesión</a
        >
      </div>
    </div>
  </nav>
  </header>

</template>