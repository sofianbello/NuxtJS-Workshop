<template>
  <div id="works-container">
    <WorkSummary class="works" v-for="work in works" :key="work" :work="works"/>

        
        <!-- <img :src="work.previewImage">
        <div class="works-title">
      {{ work.title }} 
        </div>
    <div class="works-artist">by {{ work.artist }}</div>
    <div class="works-description"> {{ work.description }}</div> -->
 
  </div>
</template>

<script>
import { ART_WORKS } from '@/content/works'

export default {
    // data() {
    //     return {
    //     works: ART_WORKS
    //     }
    // }
}
</script>

<style scoped>

</style>
