<template>
  <div>
    <v-card elevation="0">
      <v-container>
        <v-card-title>
          <h2>Portfolio</h2>
        </v-card-title>
        <v-container class="d-flex justify-center">
          <v-tabs background-color="transparent" dark color="white"
          >
            <v-tab>
              <v-btn dark color="black" rounded class="mr-8"> All </v-btn>
            </v-tab>

            <v-tab>
              <v-btn dark color="black" rounded class="mr-8"> Website </v-btn>
            </v-tab>

            <v-tab>
              <v-btn dark color="black" rounded class="mr-8">
                Mobile Application
              </v-btn>
            </v-tab>
            <v-tab>
              <v-btn dark color="black" rounded> Graphic Design </v-btn>
            </v-tab>

            <v-tab-item>
              <v-card>
                <all />
              </v-card>
            </v-tab-item>
            <v-tab-item>
              <v-card>
                <website />
              </v-card>
            </v-tab-item>
            <v-tab-item>
              <v-card>
                <mbapp />
              </v-card>
            </v-tab-item>
          </v-tabs>
        </v-container>
        <v-card-title>
          <h2>What our client say</h2>
        </v-card-title>
        <v-container>
            <v-row class="ml-4 mr-4">
            <v-col cols="12" lg="6" md="12" sm="12">
                <v-card :class="`rounded-xl`" elevation="8"> 
                    <v-container>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum nobis doloremque vel animi accusamus deleniti commodi iure autem, dignissimos iusto dolorum at, modi, temporibus impedit! Enim impedit cumque velit? Iste!
                    <br>
                    <v-avatar class="ma-5" height="60">
                        <img src="avt1.png" alt="">
                    </v-avatar> Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    </v-container>
                </v-card>
            </v-col>
            <v-col cols="12" lg="6" md="12" sm="12">
                <v-card :class="`rounded-xl`" elevation="8">
                    <v-container>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum nobis doloremque vel animi accusamus deleniti commodi iure autem, dignissimos iusto dolorum at, modi, temporibus impedit! Enim impedit cumque velit? Iste!
                   <br>
                    <v-avatar class="ma-5" height="60">
                        <img src="avt2.png" alt="">
                    </v-avatar> Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    </v-container>
                </v-card>
            </v-col>
        </v-row>
        </v-container>
      </v-container>
    </v-card>
  </div>
</template>

<script>
import all from "./all.vue";
import Mbapp from "./mbapp.vue";
import Website from "./website.vue";
export default {
  components: { all, Website, Mbapp },
};
</script>

<style>
</style>