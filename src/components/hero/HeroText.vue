<template>
  <div>
    <!-- Mobile -->
    <div v-if="$vuetify.breakpoint.xsOnly">
      <div class="title sizeL">
        <h1 class="titleS">Rogan Tong</h1>
      </div>
      <p class="subtitle sizeS brown--text text--lighten-3">WEB DEVELOPER</p>
      <p class="subtitle sizeS brown--text text--lighten-3">CREATIVE</p>
      <p class="subtitle sizeS brown--text text--lighten-3">GRADUATE IT/IS</p>
      <br>
    </div>
    <!-- Desktop -->
    <div v-else class="container">
      <div class="title">
        <h1 class="titleL">Rogan Tong</h1>
      </div>
      <div>
        <p class="subtitle sizeL brown--text text--lighten-3">WEB DEVELOPMENT  |  CREATIVE  |  GRADUATE IT/IS</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'HeroText',
    data: () => ({

    }),
     
  }
</script>

<style lang="scss" scoped>
// Main Title
body {
	background-color: #111;
}

.title {
	font-family: Arial, Helvetica, sans-serif;
	color: #FFF;
	letter-spacing: 1px;
}

h1 {
	background-image: url(https://media3.giphy.com/media/l0CRCxtNyUteI6hI4/giphy.gif?cid=ecf05e47p27s2v2lblk54vvj6e3385emi0vlpucl1etaqm03&rid=giphy.gif&ct=g);
	background-size: cover;
  background-position: center;
	color: rgba(165, 141, 141, .4);
	-moz-background-clip: text;
	-webkit-background-clip: text;
	text-transform: uppercase;
	line-height: .75;

}

.titleS{
  font-size: 18vw;
  margin-top: 10%;
  margin-bottom: 10%;
  text-align: center;
}

.titleL{
  font-size: 15vh;
  margin-top: 10%;
  margin-bottom: 10%;
  text-align: center;
}

// Subtitle CSS
.subtitle {
  font-family: Arial, Helvetica, sans-serif;
  font-weight: 100;
  color: rgba(165, 141, 141, .4);
  text-transform: uppercase;
  letter-spacing: 1em;
  left: 17%;
  animation: glitch-2 5s 5.02s infinite;
  margin-top: 5%;
}

.sizeS{
  font-size: 2.5vw;
  text-align: center;
}

.sizeL{
  font-size: 1.5vh;
}

@keyframes glitch-2 {
  1%{
    transform: rotateX(10deg) skewX(70deg);
  }
  2%{
    transform: rotateX(0deg) skewX(0deg);
  }
}

</style>