<script setup lang="ts">
import { ref } from 'vue';
import { useAuthStore } from "@/stores/index";

const usuario = ref("");
const clave = ref("");
const error = ref(false);

function onSubmit() {
  const authStore = useAuthStore();
  authStore.login(usuario.value, clave.value)
    .catch(() => error.value = true);
}
</script>

<template>
  <div class="login">
    <h1 class="title">Iniciar Sesión</h1>
    <form class="form" @submit.prevent="onSubmit">
      <label class="form-label">Usuario:</label>
      <input v-model="usuario" type="text" class="form-input" placeholder="Usuario">

      <label class="form-label">Contraseña:</label>
      <input v-model="clave" type="password" class="form-input" placeholder="Contraseña">

      <p v-if="error" class="text-danger">Usuario y/o contraseña incorrectos</p>
      <input type="submit" class="form-submit" value="Ingresar">
    </form>
  </div>
</template>

<style>
.login {
  padding: 2rem;
  background-image: url('/src/assets/images/maquillaje.jpg');
  background-size: cover;
  background-position: center;
}

.title {
  text-align: center;
}

.form {
  margin: 3rem auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 20%;
  min-width: 350px;
  max-width: 100%;
  background: rgba(19, 35, 47, 0.9);
  border-radius: 5px;
  padding: 40px;
  box-shadow: 0 4px 10px 4px rgba(185, 52, 138, 0.3);
}

.form-label {
  margin-top: 2rem;
  color: white;
  margin-bottom: 0.5rem;
}

.form-input {
  padding: 10px 15px;
  background: none;
  background-image: none;
  border: 1px solid white;
  color: white;
}

.form-submit {
  background: #1ab188;
  border: none;
  color: white;
  margin-top: 3rem;
  padding: 1rem 0;
  cursor: pointer;
  transition: background 0.2s;
}
</style>