<template>
  <div>
    <v-container>
      <v-card elevation="0">
        <v-row class="ma-0">
          <v-col lg="3" sm="12">
            <img src="graphic1.png" alt="" height="220 px" width="250 px" />
            <img src="graphic2.png" alt="" height="230 px" width="250 px" />
          </v-col>
          <v-col lg="3" sm="12">
            <img src="img3.png" alt="" height="450 px" width="250 px" />
          </v-col>
          <v-col lg="4" sm="12">
            <!-- <v-card elevation="0">
              <img src="graphic3.png" alt="" height="230 px" width="580 px" />
              <v-row>
                <v-col lg="9">
                  <img
                    src="graphic4.png"
                    alt=""
                    height="220 px"
                    width="260 px"
                  />
                </v-col>
                <v-col lg="3">
                  <img
                    src="graphic5.png"
                    alt=""
                    height="220 px"
                    width="270 px"
                  />
                </v-col>
              </v-row>
            </v-card> -->
            <v-card elevation="0">
              <!-- <img src="graphic3.png" alt="" height="230 px" width="550 px" /> -->
              <!-- <v-img src="graphic3.png"></v-img> -->
              <v-card elevation="0" img="graphic3.png"  height="210" class="mb-4"> </v-card>
              <v-row>
                <v-col cols="12" lg="9">
                  <img src="graphic4.png" alt="" height="220 px" width="260 px" />
                </v-col>
                <v-col cols="12" lg="3">
                  <img src="graphic5.png" alt="" height="220 px" width="270 px" />
                </v-col>
              </v-row>
            </v-card>
          </v-col>
        </v-row>
      </v-card>
    </v-container>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>