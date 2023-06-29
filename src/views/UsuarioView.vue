<script setup lang="ts"></script>

<template>
  <div>
    <RouterView ENDPOINT_API="usuarios"></RouterView>
    <router-link to="/usuarios/crear" class="create-user-link">Crear nuevo usuario</router-link>
  </div>
</template>

<style>
.create-user-link {
  display: block;
  margin-top: 1rem;
  color: blue;
}
</style>
