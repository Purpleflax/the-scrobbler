<script setup>
import AboutUs from '../components/AboutUs.vue'
import AlbumCoverGrid from '../components/AlbumCoverGrid.vue'
</script>
<template>
  <div class="homeRoot">
    <AboutUs />
    <AlbumCoverGrid />
  </div>
</template>
<style scoped>
.homeRoot {
  padding: 0 12%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
</style>

<script>
export default {
  name: 'HomePage',
  components: {},
  setup() {
    return {}
  }
}
</script>
