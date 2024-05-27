<template>
  <div class="grid-container">
    <div class="grid-item item1">
      <img src="../assets/albumCovers/AeroplaneOverTheSea.webp" alt="Album 1" class="album-cover" />
    </div>
    <div class="grid-item item2">
      <img src="../assets/albumCovers/BoysDontCry.webp" alt="Album 2" class="album-cover" />
    </div>
    <div class="grid-item item3">
      <img src="../assets/albumCovers/DarkSideOfTheMoon.webp" alt="Album 3" class="album-cover" />
    </div>
    <div class="grid-item item4">
      <img src="../assets/albumCovers/FooFighters.webp" alt="Album 4" class="album-cover" />
    </div>
    <div class="grid-item item5">
      <img src="../assets/albumCovers/IsThisIt.webp" alt="Album 5" class="album-cover" />
    </div>
    <div class="grid-item item6">
      <img src="../assets/albumCovers/KidA.webp" alt="Album 6" class="album-cover" />
    </div>
    <div class="grid-item item7">
      <img src="../assets/albumCovers/UnknownPleasures.webp" alt="Album 7" class="album-cover" />
    </div>
    <div class="grid-item item8">
      <img src="../assets/albumCovers/YeahYeahYeah.webp" alt="Album 8" class="album-cover" />
    </div>
    <div class="grid-item item9">
      <img src="../assets/albumCovers/AbbeyRoad.webp" alt="Album 9" class="album-cover" />
    </div>
    <div class="grid-item item10">
      <img src="../assets/albumCovers/DefinetlyMaybe.webp" alt="Album 10" class="album-cover" />
    </div>
    <div class="grid-item item11">
      <img src="../assets/albumCovers/ELO.webp" alt="Album 11" class="album-cover" />
    </div>
    <div class="grid-item item12">
      <img src="../assets/albumCovers/Igor.webp" alt="Album 12" class="album-cover" />
    </div>
    <div class="grid-item item13">
      <img src="../assets/albumCovers/NewsOfTheWorld.webp" alt="Album 13" class="album-cover" />
    </div>
    <div class="grid-item item14">
      <img src="../assets/albumCovers/strangerrrr.webp" alt="Album 14" class="album-cover" />
    </div>
    <div class="grid-item item15">
      <img src="../assets/albumCovers/Dookie.webp" alt="Album 15" class="album-cover" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'AlbumGrid'
}
</script>

<style scoped>
.grid-container {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  grid-template-rows: repeat(6, 100px);
  gap: 10px;
  max-width: 35vw;
  max-height: 40vh;
}

.grid-item {
  background-color: #2c2c2c;
  border-radius: 8px;
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
  transition:
    transform 0.3s ease,
    box-shadow 0.3s ease;
}

.grid-item:hover {
  transform: scale(1.15);
  box-shadow: 0 4px 20px rgba(255, 255, 255, 0.8);
  z-index: 1;
}

.album-cover {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.item1 {
  grid-area: 1 / 1 / 3 / 3;
}
.item2 {
  grid-area: 1 / 3 / 2 / 4;
}
.item3 {
  grid-area: 1 / 4 / 3 / 6;
}
.item4 {
  grid-area: 2 / 3 / 3 / 4;
}
.item5 {
  grid-area: 3 / 1 / 5 / 2;
}
.item6 {
  grid-area: 3 / 2 / 5 / 4;
}
.item7 {
  grid-area: 3 / 4 / 4 / 5;
}
.item8 {
  grid-area: 4 / 4 / 5 / 6;
}
.item9 {
  grid-area: 1 / 6 / 3 / 7;
}
.item10 {
  grid-area: 3 / 5 / 4 / 7;
}
.item11 {
  grid-area: 4 / 6 / 7 / 7;
}
.item12 {
  grid-area: 5 / 1 / 6 / 4;
}
.item13 {
  grid-area: 5 / 4 / 7 / 6;
}
.item14 {
  grid-area: 6 / 1 / 7 / 2;
}
.item15 {
  grid-area: 6 / 2 / 7 / 4;
}
</style>
