<script setup>
import MainHeader from './components/MainHeader.vue'
import MainFooter from './components/MainFooter.vue'
import HomePage from './views/HomePage.vue'
</script>

<template>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
    rel="stylesheet"
  />
  <div>
    <MainHeader>
      <template v-slot:left>
        <div class="inlineTitle">
          <img alt="Scrobbler Logo" src="./assets/logo.svg" style="height: 30px; width: 30px" />
          <h1 class="roboto" style="font-size: 1.3rem">The Scrobbler</h1>
        </div>
      </template>
      <template v-slot:right>
        <button>Menu</button>
      </template>
    </MainHeader>
    <HomePage />
    <MainFooter />
  </div>
</template>

<style scoped>
.inlineTitle {
  display: flex;
  align-items: center;
  gap: 10px;
}

.inlineTitle h1 {
  color: #fefefe; /* Vue.js green */
  font-size: 2rem;
  text-align: center;
  margin: 20px 0;
}

button {
  background-color: #42b983; /* Vue.js green */
  color: white;
  border: none;
  padding: 10px 20px;
  font-size: 1em;
  cursor: pointer;
  border-radius: 5px;
  margin: 10px;
}

button:hover {
  background-color: #36996f; /* Darker green for hover effect */
}
</style>
