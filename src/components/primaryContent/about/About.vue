<template>
    <v-card class="centre-me"
    tile
    dark
    id="about"
    >
    <v-row class="centre-me">
          <AboutText/>
    </v-row>
    <v-container>
      <v-row>
        <v-col
            class="fill-height ma-0"
            align="center"
            justify="center"
          >
          <v-container>
            <v-text >
              I started studying and working in the audio sector for a couple of years, moving to retail and distributions for 10 years. Working in these sectors allowed me to hone a range of transferable skills that revolved around people and management. I then decided to take a new path and completed a Bachelors in Information Sciences at 34, where my interests focused on web applications but I also studied agile principles, communication, databases and coding principles in a range of languages. My studies helped me grow a great foundation for web development. Both studies and work experience have proven my ability to meet deadlines and achieve project objectives, solve problems and prioritize critical tasks, while maintaining the high standards expected of my role and studies. What I will bring is a willingness to learn and continue to learn by myself, a mature attitude and an understanding of how important a client is to any project. I am currently working on a personal portfolio and art portfolio, while looking for a company that will continue to grow my curiosity.
            </v-text>
          </v-container>

          </v-col>
          <v-col
            class="fill-height ma-0"
            align="center"
            justify="center"
          >
            <v-container>
              <v-img
              height="400px"
              width="400px"             
              src="https://cdn.pixabay.com/photo/2020/11/16/18/57/man-5750053_1280.jpg"
              >
              </v-img>
            </v-container>
            
        </v-col>
      </v-row>
    </v-container>
    </v-card> 
</template>

<script>
import AboutText from '@/components/primaryContent/about/AboutText.vue'

export default {
    name: 'Projects',
    data: () => ({

    }),
    components: {
      AboutText,  
    }, 
  }
</script>

<style scoped>
.centre-me {
    justify-content: center;
}

</style>>