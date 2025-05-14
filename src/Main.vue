<script setup>

</script>

<template>
    <main>
      <section class="about">
        <h2>Sobre Mim</h2>
        <p>Sou estudante do ensino médio no SESI e faço curso técnico em Desenvolvimento de Sistemas no SENAI. Nos finais de semana eu trabalho, sempre buscando crescer e conquistar meu espaço no mundo. Tenho interesse em pessoas, tecnologia e saúde!</p>
      </section>

      <section class="info">
        <h2>Minha Rotina</h2>
        <ul>
          <li>📚 Estudo no SESI (Ensino Médio)</li>
          <li>💻 Curso Desenvolvimento no SENAI</li>
          <li>👜 Trabalho nos finais de semana</li>
        </ul>
      </section>

      <section class="contact">
        <h2>Contato</h2>
        <p>Email: <a href="carolina.t.m.bastos@gmail.com">carolina.t.m.bastos@gmail.com</a></p>
        <p>Instagram: <a href="https://instagram.com/seuuser" target="_blank">@carolbastoss</a></p>
      </section>
    </main>
 
</template>

<style scoped>
main section {
  margin-bottom: 30px;
}

h2 {
  font-size: 22px;
  margin-bottom: 10px;
  color: #e91e63;
  border-left: 4px solid #e91e63;
  padding-left: 10px;
}

p, li {
  font-size: 16px;
}

ul {
  list-style: none;
  padding-left: 0;
}

ul li::before {
  content: "🌸 ";
  margin-right: 8px;
}

a {
  color: #d63384;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
</style>

