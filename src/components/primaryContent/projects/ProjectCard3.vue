<template>
  <v-card
    class="mx-3 mb-5"
    max-width="300"
    dark
  >
    <v-img
        class="white--text align-end"
        height="200px"
        src="https://media0.giphy.com/media/l3vRmVv5P01I5NDAA/giphy.gif?cid=ecf05e47pbw8g4do2yhtf9ygs6hl4d8gxlkn5yrsewcwzzhc&rid=giphy.gif&ct=g" 
      >
        <v-card-title text="purple lighten-3">Bird Gen Api</v-card-title>
    </v-img>

    <v-card-text>
        <div>BUILT WITH.</div>
        <div div>Express, Node, Heroku and MongoDB</div>
    </v-card-text>

    <v-card-actions>
      <v-btn
        color="purple lighten-3"
        text
        href="https://bird-quizapi.herokuapp.com/quiz"
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
    name: "ProjectCard3"

}
</script>

<style scoped>

</style>