<template>
    <v-card class="centre-me"
    tile
    color="deep-purple lighten-4"
    id="project"
    >
      <v-container id="anchor-projects">
        <v-row class="centre-me">
          <ProjectText/>
        </v-row>
        <v-row class="centre-me">
            <ProjectCard1/>
            <ProjectCard2/>
            <ProjectCard3/>
            <ProjectCard4/>
            <ProjectCard5/>
            <ProjectCard6/>
        </v-row> 
        <br><br> 
      </v-container>   
    </v-card> 
</template>

<script>
import ProjectText from '@/components/primaryContent/projects/ProjectText.vue'
import ProjectCard1 from '@/components/primaryContent/projects/ProjectCard1.vue'
import ProjectCard2 from '@/components/primaryContent/projects/ProjectCard2.vue'
import ProjectCard3 from '@/components/primaryContent/projects/ProjectCard3.vue'
import ProjectCard4 from '@/components/primaryContent/projects/ProjectCard4.vue'
import ProjectCard5 from '@/components/primaryContent/projects/ProjectCard5.vue'
import ProjectCard6 from '@/components/primaryContent/projects/ProjectCard6.vue'

export default {
    name: 'Projects',
    data: () => ({

    }),
    components: {
      ProjectText,
      ProjectCard1,
      ProjectCard2,
      ProjectCard3,
      ProjectCard4,
      ProjectCard5,
      ProjectCard6,
      

      
    }, 
  }
</script>

<style scoped>
.centre-me {
    justify-content: center;
}

</style>>