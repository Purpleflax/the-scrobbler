<template>
  <div>
    <div class="mainText">
      Seamlessly Scrobble<br />
      Historical Listening<br />
      Data to <span class="lastFM">Last.fm</span>
    </div>
    <div class="subText">
      <p>
        From streaming services such as <span class="spotify">Spotify</span> and
        <span class="appleMusic">Apple Music</span>
      </p>
    </div>
  </div>
</template>
<script>
export default {
  name: 'AboutUs',
  components: {},
  setup() {
    return {}
  }
}
</script>
<style scoped>
.mainText {
  font-size: 3.5rem;
  font-weight: 700;
  text-align: justify;
  margin-top: 10vh;
  width: 100%;
  max-width: 35vw;
  max-height: 30vh;
}

.subText {
  margin-top: 5vh;
}

.lastFM {
  background: linear-gradient(90deg, #d51007, #ff6666);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-style: italic;
}

.spotify {
  background: linear-gradient(90deg, #1db954, #1af667);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-style: italic;
  font-weight: 700;
}

.appleMusic {
  background: linear-gradient(90deg, #ff2d55, #ff5a5f);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-style: italic;
  font-weight: 700;
}
</style>
