<template>
  <v-app>
    
    <v-main>
      <hf />
    <Nuxt />
    
  </v-main>
  <foter />
  </v-app>
</template>

<script>
import Foter from '../components/foter.vue'
import hf from '../components/hf.vue'
export default {
  components: { hf, Foter },

}
</script>

<style>

</style>