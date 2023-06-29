
<script setup lang="ts"></script>

<template>
  <div>
    <RouterView ENDPOINT_API="productos"></RouterView>
    <router-link to="/productos/crear" class="create-product-link">Crear nuevo producto</router-link>
  </div>
</template>

<style>
.create-product-link {
  display: block;
  margin-top: 1rem;
  color: blue;
}
</style>
