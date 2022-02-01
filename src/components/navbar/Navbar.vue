<template>
  <div>
    <!-- Mobile -->
    <v-app-bar v-if="$vuetify.breakpoint.xsOnly"
      dense
      dark >
      <v-toolbar-title><Title/></v-toolbar-title>
      <v-spacer></v-spacer>
      <Drawer/>
    </v-app-bar>
    <!-- Desktop -->
    <v-app-bar v-else
      dense
      dark
    >
        <v-toolbar-title><Title/></v-toolbar-title>
        <v-spacer></v-spacer>
        <v-btn
          plain
          text
          class="brown--text text--lighten-3"
          @click="$vuetify.goTo('#project')"
        >
          PROJECTS
        </v-btn>

        <v-btn
          plain
          text
          class="brown--text text--lighten-3"
          @click="$vuetify.goTo('#about')"
        >
          ABOUT
        </v-btn>

        <v-btn
          plain
          text
          class="brown--text text--lighten-3"
          href="resume.pdf"
          download>
          Résumé
        </v-btn>

        <v-btn icon href="http://www.instagram.com/rogiebeer">
          <v-icon class="brown--text text--lighten-4">mdi-instagram</v-icon>
        </v-btn>
        <v-btn icon href="https://github.com/rogieBeer">
          <v-icon class="brown--text text--lighten-4">mdi-github</v-icon>
        </v-btn>
    </v-app-bar>
  </div>
</template>

<script>
  import Title from '@/components/navbar/Title.vue'
  import Drawer from '@/components/navbar/Drawer.vue'

  export default {
    name: 'Navbar',
    data: () => ({

    }),
    components: {
      Title,
      Drawer,
      
    },
    methods: {
      readFile() {
        window.open('src/assets/Resume.pdf', '_blank') //to open in new tab
      }
    }
  }
</script>
