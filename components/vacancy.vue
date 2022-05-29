<template>
  <div>
        <v-container class="mt-8">
            <v-card  elevation="0" > 
            <v-tabs background-color="transparent" vertical>
            <v-card outlined >
                <v-tab>
              <v-card-title >
                Frontend Developer
            </v-card-title>
            </v-tab>
            <v-divider></v-divider>

            <v-tab>
              <v-card-title>
                Backend Developer
            </v-card-title>
            </v-tab>
            <v-divider></v-divider>
            <v-tab>
              <v-card-title>
                UI/UX Designer
            </v-card-title>
            </v-tab>
            <v-divider></v-divider>

            <v-tab>
              <v-card-title>
                Graphic Designer
            </v-card-title>
            </v-tab>
            <v-divider></v-divider>

            <v-tab>
              <v-card-title>
                Frontend
            </v-card-title>
            </v-tab>
            <v-divider></v-divider>
            </v-card>

            <v-tab-item>
              <v-card>
                <frntdev />
              </v-card>
            </v-tab-item>
            <v-tab-item>
              <v-card>
                <bck />
              </v-card>
            </v-tab-item>
            <v-tab-item>
              <v-card>
                <ui />
              </v-card>
            </v-tab-item>
          </v-tabs>
            
        </v-card>
        </v-container>
  </div>
</template>

<script>
import Bck from './bck.vue';
import frntdev from './frntdev.vue';
import Ui from './ui.vue';
export default {
  components: { frntdev, Bck, Ui },};
</script>

<style>
</style>