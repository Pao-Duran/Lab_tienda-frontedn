<script setup lang="ts"></script>

<template>
  <div>
    <RouterView ENDPOINT_API="personas"></RouterView>
    <router-link to="/personas/crear" class="create-person-link">Crear nuevo Cliente</router-link>
  </div>
</template>

<style>
.create-person-link {
  display: block;
  margin-top: 1rem;
  color: blue;
}
</style>
