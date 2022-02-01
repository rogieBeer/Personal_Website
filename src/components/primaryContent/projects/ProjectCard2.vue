<template>
  <v-card
    class="mx-3 mb-5"
    max-width="300"
    dark
  >
    <v-img
        class="white--text align-end"
        height="200px"
        src="https://media1.giphy.com/media/1yTefmRbToEr3WRpLO/giphy.gif?cid=790b7611fd37243ad69a9aae71b462e17b57c3ed57a8d1cf&rid=giphy.gif&ct=g" 
      >
        <v-card-title>Bird Quiz Website</v-card-title>
    </v-img>

    <v-card-text>
        <div>BUILT WITH.</div>
        <div div>Vue3, Express, Node, Heroku and MongoDB</div>
    </v-card-text>

    <v-card-actions>
      <v-btn
        color="purple lighten-3"
        text
        href="https://the-little-bird-website.herokuapp.com/"
      >
        Site
      </v-btn>
      <v-btn
        color="purple lighten-3"
        text
      >
        Info
      </v-btn>
    </v-card-actions>
  </v-card>
</template>

<script>
export default {
    name: "ProjectCar2"

}
</script>

<style scoped>

</style>