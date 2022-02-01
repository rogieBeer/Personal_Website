<template>
  <div>
    <!-- Mobile -->
    <div v-if="$vuetify.breakpoint.xsOnly">
      <div class="title">
        <h1 class="titleS">About Me</h1>
      </div>
    </div>
    <!-- Desktop -->
    <div v-else class="container">
      <div class="title">
        <h1 class="titleL">About Me</h1>
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
    text-align: center;
}

.title {
	font-family: Arial, Helvetica, sans-serif;
	color: #FFF;
	display: flex;
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
    text-align: center;

}

.titleS{
  font-size: 10vw;
  text-align: center;
  margin-top: 20%;
  margin-bottom: 20%;
}

.titleL{
  font-size: 5vw;
  margin-top: 10%;
  margin-bottom: 20%;
}

</style>