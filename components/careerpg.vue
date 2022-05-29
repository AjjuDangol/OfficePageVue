<template>
  <div>
    <!-- <v-card img="career.png" height="400"> </v-card> -->
    <v-img src="career.png"></v-img>
    <v-container>
        <v-card-title>
            <h2>
            Are you intrested to join us?
        </h2>
        </v-card-title>
        <v-card-title>
            Our Vacancies
        </v-card-title>

        <v-tabs background-color="transparent" dark color="white">
            <v-tab>
              <v-btn dark color="black" rounded class="mr-8"> Vacancies </v-btn>
            </v-tab>

            <v-tab>
              <v-btn dark color="black" rounded class="mr-8"> Internship </v-btn>
            </v-tab>

            <v-tab>
              <v-btn dark color="black" rounded class="mr-8">
                Traineeship
              </v-btn>
            </v-tab>

            <v-tab-item>
              <v-card elevation="0">
                <vacancy />
              </v-card>
            </v-tab-item>
            <v-tab-item>
              <v-card elevation="0">
                <vacancy />
              </v-card>
            </v-tab-item>
            <v-tab-item>
              <v-card>
                <vacancy />
              </v-card>
            </v-tab-item>
          </v-tabs>
    </v-container>
  </div>
</template>

<script>
import vacancy from './vacancy.vue';
export default {
  components: { vacancy },};
</script>

<style>
</style>