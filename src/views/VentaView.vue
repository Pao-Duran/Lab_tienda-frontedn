<script setup lang="ts"></script>

<template>
  <div>
    <RouterView ENDPOINT_API="ventas"></RouterView>
    <router-link to="/ventas/crear" class="create-sale-link">Crear nueva venta</router-link>
  </div>
</template>

<style>
.create-sale-link {
  display: block;
  margin-top: 1rem;
  color: blue;
}
</style>
