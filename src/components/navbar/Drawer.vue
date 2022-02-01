// Menu for mobile
<template>
    <v-menu
            dark
            bottom
            left
          >
            <template v-slot:activator="{ on, attrs }">
              <v-btn
                icon
                v-bind="attrs"
                v-on="on"
              >
                <v-icon class="brown--text text--lighten-3">mdi-dots-vertical</v-icon>
              </v-btn>
            </template>

            <v-list>
              <v-list-item @click="$vuetify.goTo('#project')">
                <v-list-item-title 
                  class="brown--text text--lighten-3">Projects
                </v-list-item-title>
              </v-list-item>
              <v-list-item @click="$vuetify.goTo('#about')">
                <v-list-item-title 
                  class="brown--text text--lighten-3">About
                </v-list-item-title>
              </v-list-item>
              <v-list-item href="resume.pdf" download>
                <v-list-item-title 
                  class="brown--text text--lighten-3">Résumé
                </v-list-item-title>
              </v-list-item>
            </v-list>
          </v-menu>       
</template>

<script>
  export default {
    data: () => ({
      items: [
        { title: 'Projects' },
        { title: 'Resume' },
        { title: 'About' },
        { title: 'Github' },
      ],
    }),
  }
</script>