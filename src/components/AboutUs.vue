<template>
  <div>
    <div class="mainText">
      Seamlessly Scrobble<br />
      Historical Listening<br />
      Data to <span class="lastFM">Last.fm</span>
    </div>
    <div class="subText">
      <p>
        Simply upload your historical listening data from
        <span class="spotify">Spotify</span> or
        <span class="appleMusic">Apple Music</span>
        <br />
        and we'll take care of the rest.
      </p>
    </div>
    <div class="authButtonWrapper">
      <button class="authButton">Login with Last.fm</button>
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
  line-height: 1.5em;
}

.subText {
  margin-top: 5vh;
  line-height: 2.5em;
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

.authButtonWrapper {
  margin-top: 5vh;
}

.authButton {
  background-color: var(--background-color);
  color: var(--text-color);
  border: none;
  padding: 10px 20px;
  font-size: 1rem;
}
</style>
