<script setup></script>

<template>
  <div class="footerWrapper">
    <a href="https://github.com/Purpleflax/the-scrobbler" target="_blank" rel="noopener noreferrer">
      <img src="../assets/github-mark-white.svg" class="footerIcon" />
    </a>
    <a href="https://www.x.com" target="_blank" rel="noopener noreferrer">
      <img src="../assets/xlogo.svg" class="footerIcon" />
    </a>
    <a href="https://www.discord.com" target="_blank" rel="noopener noreferrer">
      <img src="../assets/discord-mark-white.svg" class="footerIcon" />
    </a>
  </div>
</template>

<style scoped>
.footerWrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px;
  border-top: 1px solid #23333d;
  box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1);
  position: fixed;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1000;
}

.footerIcon {
  height: 30px;
  width: 30px;
  margin: 0 10px;
}
</style>
