<template>
  <div>
    <!-- <v-card img="contact.png" height="400" elevation="0" class="mb-8"> </v-card> -->
    <v-img src="contact.png" class="mb-8"></v-img>
    <v-card :class="`rounded-xl`" class="d-flex justify-center">
      <v-row class="d-flex justify-center">
        <v-col cols="12" md="2">
          <v-icon color="black"> mdi-map-marker </v-icon>
      Gyaneshwor, Kathmandu
        </v-col>
        <v-col cols="12" md="2">
          <v-icon class="ml-8" color="black"> mdi-email </v-icon>
      asd@gmail.com
        </v-col>
        <v-col cols="12" md="2">
          <v-icon class="ml-8" color="black"> mdi-phone </v-icon>
      +977-9876548976
        </v-col>
      </v-row>
      
      

      
    </v-card>
    <v-container>
      <v-row>
        <v-col cols="12" lg="6" md="12" sm="12">
          <v-img src="ct2.png" ></v-img>
            <!-- <img src="ct2.png" alt="" height="750" width="750" class="mt-8" /> -->
          
        </v-col>
        <v-col cols="12" lg="6" md="12" sm="12">
          <v-card class="mt-16" :class="`rounded-xl`" >
            <v-container>
                <v-card-title> First name </v-card-title>
            <v-text-field outlined> </v-text-field>
            <v-card-title> Last name </v-card-title>
            <v-text-field outlined> </v-text-field>
            <v-card-title> Email </v-card-title>
            <v-text-field outlined> </v-text-field>
            <v-card-title> Address </v-card-title>
            <v-text-field outlined> </v-text-field>
            <v-card-title> Message </v-card-title>
            <v-textarea outlined> </v-textarea>
            </v-container>
            <v-container class="d-flex justify-center ma-4 pb-12" >
                <v-btn color="black" dark rounded>
                    Contact Us
                </v-btn>
            </v-container>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>