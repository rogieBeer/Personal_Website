<template>
  <v-card
    class="mx-3 mb-5"
    max-width="300"
    dark
  >
    <v-img
      class="white--text align-end"
      height="200px"
      src="https://media3.giphy.com/media/l0CRCxtNyUteI6hI4/giphy.gif?cid=ecf05e47p27s2v2lblk54vvj6e3385emi0vlpucl1etaqm03&rid=giphy.gif&ct=g"
    >
      <v-card-title>Personal Portfolio</v-card-title>
    </v-img>

    <v-card-text>
      <div>BUILT WITH.</div>
      <div>Vue2, Vuetify and Firebase</div>
    </v-card-text>

    <v-card-actions>
      <v-btn
        color="purple lighten-3"
        text
        href="/"
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
    name: "ProjectCard1"

}
</script>

<style scoped>

</style>