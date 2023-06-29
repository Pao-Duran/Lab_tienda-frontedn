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
        </ul>
          <div class="cart relative utils__item ">
            <a href="/cart">
              <span class="cart-icon">
                <svg class="desktop-icon" viewBox="-3 -1 23 25" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                  <g stroke-width="2">
                    <path d="M10.5882353,8 L10.5882353,4.08823529 C10.5882353,2.93493479 9.65330051,2 8.5,2 C7.34669949,2 6.41176471,2.93493479 6.41176471,4.08823529 L6.41176471,8 L2,8 L2,20 L15,20 L15,8 L10.5882353,8 Z M4.41176471,4.08823529 C4.41176471,1.83036529 6.24212999,0 8.5,0 C10.75787,0 12.5882353,1.83036529 12.5882353,4.08823529 L12.5882353,6 L17,6 L17,22 L0,22 L0,6 L4.41176471,6 L4.41176471,4.08823529 Z M5.41176471,6 L4.41176471,7 L4.41176471,6 L5.41176471,6 Z"></path>
                    <polygon points="4 8 4 6 13 6 13 8"></polygon>
                  </g>
                </svg>
                <span class="icon-fallback-text">Carrito</span>
              </span>
              </a>
          </div>
        </div>
      </div>

  </nav>
  </header>

</template>