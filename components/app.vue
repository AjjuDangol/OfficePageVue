<template>
  <div>
    <!-- <v-card img="serv1.png" height="400"></v-card> -->
    <v-img src="serv1.png"></v-img>
    <v-container>
      <v-card-title>
        <h2>Application Development</h2>
      </v-card-title>
      <br />
      <v-card-subtitle>
        <h2>Our Application Development service</h2>
      </v-card-subtitle>

      <v-row>
        <v-col cols="12" lg="6" sm="12" md="12">
          <v-card-text>
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Veritatis,
            eius. Sunt itaque velit a vitae repudiandae facilis dolor officia
            corrupti dolores sed nobis, doloribus delectus autem necessitatibus
            animi quis eos! Lorem ipsum dolor sit, amet consectetur adipisicing
            elit. Debitis odit obcaecati neque dolorum eum quas quisquam ut
            doloremque eaque possimus suscipit, ab ducimus magnam deserunt porro
            laboriosam voluptatem? Veritatis, a! Lorem ipsum dolor sit amet
            consectetur adipisicing elit. Reprehenderit exercitationem eligendi
            perferendis esse. Amet officiis delectus magnam aut. Provident
            debitis fugit atque beatae saepe aliquid! Amet fuga tempora
            voluptates eius. Lorem ipsum dolor, sit amet consectetur adipisicing
            elit. Sunt, accusamus molestias laudantium corrupti natus excepturi
            sapiente doloribus quasi ducimus saepe, ad a ullam pariatur vitae
            veniam consectetur. Nihil, quaerat labore. Lorem, ipsum dolor sit
            amet consectetur adipisicing elit. Rerum, a nostrum cum aliquid
            minus architecto, fuga optio quisquam id assumenda fugiat harum
            facilis nam dolorem voluptas eos, magni qui inventore. Lorem, ipsum
            dolor sit amet consectetur adipisicing elit. Explicabo earum amet
            sed, iure mollitia quo, aspernatur odio tempore laudantium
            accusantium natus quaerat et ratione ipsam quisquam voluptatibus
            consequatur nostrum laboriosam? Lorem ipsum dolor sit amet
            consectetur, adipisicing elit. Nemo cum, recusandae ipsa, sequi
            possimus vero distinctio ullam ipsum ea commodi delectus voluptates
            vel aspernatur ratione nostrum praesentium aperiam sit maxime! Lorem
            ipsum dolor sit amet consectetur adipisicing elit. Maiores aperiam
            ipsum facere culpa nemo ex inventore doloremque nam enim, fugit
            ratione amet repudiandae doloribus, at corporis dolor, libero
            quibusdam cupiditate!
          </v-card-text>
        </v-col>
        
        <v-col cols="12" lg="6" sm="12" md="12">
          <!-- <v-card img="app.png" class="mr-8" height="535" elevation="0"> </v-card>-->
            <!-- <img src="app.png" alt="" class="mr-8" height="535" /> -->
            <v-img src="app.png"></v-img>
           
        </v-col>
      </v-row>
      <v-card-title><h2>Our recent app design</h2></v-card-title>   
      <v-container>
          <mbapp />
      </v-container>
    </v-container>
  </div>
</template>

<script>
import mbapp from './mbapp.vue';
export default {
  components: { mbapp },};
</script>

<style>
</style>