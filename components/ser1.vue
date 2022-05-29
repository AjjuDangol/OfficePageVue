<template>
  <div>
      <!-- <v-card img="serv1.png" height="400" elevation="0"></v-card> -->
      <v-img src="serv1.png"></v-img>
      <v-container>
                  <v-row class="pt-12 pr-12 pl-12 mt-12">
          <v-col cols="12" lg="4" md="12" sm="12">
              <NuxtLink to="/webservice">
            <v-card :class="`rounded-xl`">
              <img src="card1.png" alt="" height="150" />
              <v-container>
                <h4>Website Development</h4>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                Aperiam expedita beatae est cupiditate quae eos voluptatum eum,
              </v-container>
            </v-card>
              </NuxtLink>
          </v-col>
          <v-col cols="12" lg="4" md="12" sm="12">
               <NuxtLink to="/appservice">
            <v-card :class="`rounded-xl`">
              <img src="card2.png" alt="" height="150" />
              <v-container>
                <h4>Application Development</h4>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                Aperiam expedita beatae est cupiditate quae eos voluptatum eum,
              </v-container>
            </v-card>
               </NuxtLink>
          </v-col>
          <v-col cols="12" lg="4" md="12" sm="12" >
              <NuxtLink to="/graphicdesign">
            <v-card :class="`rounded-xl`">
              <img src="card3.png" alt="" height="150" />
              <v-container>
                <h4>Graphic Design</h4>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                Aperiam expedita beatae est cupiditate quae eos voluptatum eum,
              </v-container>
            </v-card>
              </NuxtLink>
          </v-col>
        </v-row>
      </v-container>
      <v-container>
          <v-row class="pb-12 pr-12 pl-12 ">
            <v-col
            cols="12"
              sm="12"
              lg="4"
              md="12"
              v-for="card in cards"
              :key="card.title"
            >
              <v-card :class="`rounded-xl`">
                <v-img
                  :src="card.src"
                  height="150px"
                  width="140"
                >
                </v-img>
                <v-container>
                    <v-card-title><h4>{{card.title}}</h4></v-card-title>
                <v-card-subtitle v-text="card.text" ></v-card-subtitle>
                </v-container>
                
              </v-card>
            </v-col>
          </v-row>
      </v-container>
  </div>
</template>

<script>
export default {
    data: () => ({
    cards: [
      {
        src: "s1.png",
        flex: 4,
        title:"Logo Design",
         text:"Lorem ipsum dolor sit amet, consectetur adipisicing elit.Aperiam expedita beatae est cupiditate quae eos voluptatum eum,"
      },
      {
        src: "s2.png",
        flex: 4,
        title:"Content Writing",
         text:"Lorem ipsum dolor sit amet, consectetur adipisicing elit.Aperiam expedita beatae est cupiditate quae eos voluptatum eum,"
      },
      {
        src: "s3.png",
        flex: 4,
        title:"UI/UX Design",
         text:"Lorem ipsum dolor sit amet, consectetur adipisicing elit.Aperiam expedita beatae est cupiditate quae eos voluptatum eum,"
      },
      {
        src: "s4.png",
        title:"Digital Marketing",
         text:"Lorem ipsum dolor sit amet, consectetur adipisicing elit.Aperiam expedita beatae est cupiditate quae eos voluptatum eum,"
      },
    ],
  }),

}
</script>

<style>

</style>