<script setup lang="ts"></script>

<template>
  <div>
    <RouterView ENDPOINT_API="categorias"></RouterView>
    <router-link to="/categorias/crear" class="create-catalog-link">Crear nuevo catálogo</router-link>
  </div>
</template>

<style>
.create-catalog-link {
  display: block;
  margin-top: 1rem;
  color: blue;
}
</style>

