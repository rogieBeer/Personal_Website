<template>
  <div>
    <!-- Mobile -->
    <div v-if="$vuetify.breakpoint.xsOnly">
      <div class="title">
        <h1 class="titleS">Projects</h1>
      </div>
    </div>
    <!-- Desktop -->
    <div v-else class="container">
      <div class="title">
        <h1 class="titleL black-outline">Projects</h1>
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
	background-image: url(https://media4.giphy.com/media/xT9IgzoKnwFNmISR8I/giphy.gif?cid=790b7611debd6280066af226678a05486517e5372532ef80&rid=giphy.gif&ct=g);
	background-size: cover;
    background-position: bottom;
	color: transparent;
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

.black-outline{
    -webkit-text-stroke: 1.11px black; /* stroke width and color */
    color: transparent;
    -webkit-font-smoothing: antialiased;
}

</style>