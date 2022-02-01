<template>
    <v-card class="centre-me"
    dark
    tile
    >
      <v-container>
        <v-row justify="center">
          <HeroText/>  
        </v-row>
        <v-row justify="center">
          <v-img
            class="white--text align-end"
            max-width="120px"
            src="@/assets/Shirt.png"
          >
          </v-img>
        </v-row>
        <v-row justify="center">
          <Arrow/>
        </v-row>  
      </v-container>   
    </v-card> 
</template>

<script>
import HeroText from '@/components/hero/HeroText.vue'
import Arrow from '@/components/hero/Arrow.vue'
export default {
    name: 'Hero',
    data: () => ({

    }),
    components: {
      HeroText,
      Arrow,
      
    }, 
  }
</script>

<style scoped>
.centre-me {
    height: 80vh;
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>>

