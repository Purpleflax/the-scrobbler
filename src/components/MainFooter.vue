<script setup></script>

<template>
  <div class="footerWrapper">
    <button>Github</button>
    <button>Twitter</button>
    <button>Discord</button>
  </div>
</template>

<style scoped>
.footerWrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px;
  border-top: 1px solid #e0e0e0;
  box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1);
  position: fixed;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1000;
}
</style>
