<script setup>
import MainHeader from './components/MainHeader.vue'
import MainFooter from './components/MainFooter.vue'
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
          <h1 style="font-size: 1rem">The Scrobbler</h1>
        </div>
      </template>
      <template v-slot:right>
        <button style="margin-right: 1vw">Login</button>
      </template>
    </MainHeader>
    <RouterView />
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
  color: #fefefe;
  font-size: 2rem;
  text-align: center;
}

button {
  background-color: var(--background-color);
  color: var(--text-color);
  border: none;
  padding: 10px 20px;
  font-size: 1rem;
}

button:hover {
  /* Transition text to a grey */
  color: #7e7e7e;
  animation: 0.3s ease-in-out;
  transition: 0.3s ease-in-out;
  cursor: pointer;
}
</style>

<script>
export default {
  name: 'App',
  components: {
    MainHeader,
    MainFooter
  },
  created() {
    document.title = 'The Scrobbler'
  }
}
</script>
