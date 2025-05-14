<script setup>

</script>

<template>
   <header class="profile-header">
      <img src="https://i.pinimg.com/736x/fd/7d/9c/fd7d9c52e7f7e06ecdd38aa3c6912424.jpg" alt="Foto de Perfil" class="profile-img"/>
      <h1>Oi, eu sou a Carol!!</h1>
      <p class="tagline">Estudante • Dev no SENAI • Futura Terapeuta </p>
    </header>
</template>

<style scoped>
.profile-header {
  text-align: center;
  margin-bottom: 30px;
}

.profile-img {
  width: 140px;
  height: 140px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid #ff91c1;
  margin-bottom: 15px;
}

.profile-header h1 {
  font-size: 32px;
  color: #d63384;
}

.tagline {
  font-style: italic;
  color: #a64dff;
}

</style>
