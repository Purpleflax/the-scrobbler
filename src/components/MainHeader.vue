<script setup></script>

<template>
  <div class="headerWrapper">
    <slot name="left"></slot>
    <slot name="center"></slot>
    <slot name="right"></slot>
  </div>
</template>

<style scoped>
.headerWrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 20px;
  margin: 0;
  border-bottom: 1px solid #e0e0e0;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
</style>
