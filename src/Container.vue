<script setup>
import Header from "./Header.vue"
import Main from "./Main.vue"
import Footer from "./Footer.vue"

</script>

<template>
    <div class="container">
        <Header />
        <Main />
        <Footer />

  </div>
</template>

<style scoped>
.container {
  max-width: 800px;
  margin: 50px auto;
  background: #ffffff;
  border-radius: 20px;
  padding: 30px;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
}
</style>