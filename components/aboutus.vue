<template>
  <div>
    <!-- <v-card img="about.png" height="400"> </v-card> -->
    <v-img src="about.png"></v-img>
    <v-card elevation="0">
      <v-container class="d-flex justify-center">
        <v-card-title>
          <h2>About Us</h2>
        </v-card-title>
      </v-container>
      <v-container>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga saepe
        optio ipsa non aspernatur perferendis ad a blanditiis! Molestiae
        delectus nesciunt impedit velit pariatur sequi voluptate dolore illum
        vero! Illo. Lorem ipsum dolor sit, amet consectetur adipisicing elit.
        Similique, alias totam! Aliquid impedit esse saepe aliquam corrupti, in
        quo accusantium. Autem reiciendis pariatur ducimus quos sint cupiditate
        iusto voluptatem hic! Lorem ipsum dolor sit amet consectetur adipisicing
        elit. Atque, omnis nesciunt. Sed mollitia repudiandae, perferendis magni
        quo voluptatum culpa? Hic ratione laudantium, debitis harum nobis
        consequuntur soluta magnam iusto esse. Lorem ipsum, dolor sit amet
        consectetur adipisicing elit. Neque, tempora assumenda ipsam, corporis
        perspiciatis, quia similique maxime repudiandae magnam fuga inventore
        veniam quos. Eos, beatae doloribus mollitia quasi dolorem blanditiis.
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga saepe
        optio ipsa non aspernatur perferendis ad a blanditiis! Molestiae
        delectus nesciunt impedit velit pariatur sequi voluptate dolore illum
        vero! Illo. Lorem ipsum dolor sit, amet consectetur adipisicing elit.
        Similique, alias totam! Aliquid impedit esse saepe aliquam corrupti, in
        quo accusantium. Autem reiciendis pariatur ducimus quos sint cupiditate
        iusto voluptatem hic! Lorem ipsum dolor sit amet consectetur adipisicing
        elit. Atque, omnis nesciunt. Sed mollitia repudiandae, perferendis magni
        quo voluptatum culpa? Hic ratione laudantium, debitis harum nobis
        consequuntur soluta magnam iusto esse. Lorem ipsum, dolor sit amet
        consectetur adipisicing elit. Neque, tempora assumenda ipsam, corporis
        perspiciatis, quia similique maxime repudiandae magnam fuga inventore
        veniam quos. Eos, beatae doloribus mollitia quasi dolorem blanditiis.
      </v-container>
      <v-card elevation="0">
        <v-container>
          <v-row>
            <v-col cols="12" md="6">
              <v-card-title>
                <h2>Why choose us?</h2>
              </v-card-title>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos
              distinctio tenetur, itaque cumque animi excepturi?
              <v-card-title>
                <h3>1. Full time support</h3>
              </v-card-title>

              <v-card-text class="ml-6">
                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                Sapiente temporibus voluptatibus dicta voluptatum atque
                quibusdam.
              </v-card-text>
              <v-card-title>
                <h3>2. Expert Teams</h3>
              </v-card-title>
              <v-card-text class="ml-6">
                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                Sapiente temporibus voluptatibus dicta voluptatum atque
                quibusdam.
              </v-card-text>
              <v-card-title>
                <h3>3. Fast and Quality product</h3>
              </v-card-title>
              <v-card-text class="ml-6">
                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                Sapiente temporibus voluptatibus dicta voluptatum atque
                quibusdam.
              </v-card-text>
            </v-col>
            <v-col cols="12" md="6">
              <v-card elevation="0" class="mt-14 pt-4">
                <v-row>
                  <v-col cols="12" md="10">
                    <!-- <v-card img="abt1.png"
                        ><v-row>
                          <v-col cols="12" md="6"> </v-col>
                          <v-col cols="12" md="6">
                          <img
                            src="abt2.png"
                            alt=""
                            height="120"
                            class="" /></v-col></v-row
                    ></v-card> -->
                    <v-img src="abt1.png" > <img src="abt2.png" alt="" height="250" class=" mt-16 ml-12 pl-12"></v-img>
                  </v-col>
                  <!-- <v-col cols="12" md="8" class="pt-0 mt-0 ml-16">
                    <v-img
                      src="abt2.png"
                    >
                    </v-img>
                  </v-col> -->
                </v-row>
              </v-card>
            </v-col>
          </v-row>
        </v-container>
      </v-card>
      <v-container>
        <v-card :class="`rounded-lg`" elevation="8">
          <v-row>
            <v-col lg="3" sm="6">
              <v-container>
                <v-row>
                  <v-col cols="5"><h2>1000+</h2> </v-col>
                  <v-col>
                    <img src="sm1.png" alt="" height="50" />
                  </v-col>
                </v-row>
                <br />
                <h3 class="ml-2">Project Development</h3>
              </v-container>
            </v-col>
            <v-divider vertical light></v-divider>
            <v-col cols="12" lg="3" sm="6">
              <v-container>
                <v-row>
                  <v-col cols="4">
                    <h2>100+</h2>
                  </v-col>
                  <v-col>
                    <img src="sm2.png" alt="" height="50" />
                  </v-col>
                </v-row>
                <br />
                <h3>Clients</h3>
              </v-container>
            </v-col>
            <v-divider vertical light></v-divider>
            <v-col cols="12" lg="3" sm="6">
              <v-container>
                <v-row>
                  <v-col cols="4">
                    <h2>500+</h2>
                  </v-col>
                  <v-col>
                    <img src="sm3.png" alt="" height="50" />
                  </v-col>
                </v-row>
                <br />
                <h3>Recieved Review</h3>
              </v-container>
            </v-col>
            <v-divider vertical light></v-divider>
            <v-col cols="12" lg="3" sm="6">
              <v-container>
                <v-row>
                  <v-col cols="4">
                    <h2>100+</h2>
                  </v-col>
                  <v-col>
                    <img src="sm4.png" alt="" height="50" />
                  </v-col>
                </v-row>

                <br />
                <h3>Recieved Rewards</h3>
              </v-container>
            </v-col>
          </v-row>
        </v-card>
      </v-container>
      <v-container class="d-flex justify-center mt-3">
        <v-card-title>
          <h2>Team Members</h2>
        </v-card-title>
      </v-container>
      <v-container>
        <v-row class="justify-center pa-12">
          <v-col
            cols="12"
            sm="12"
            lg="4"
            md="6"
            v-for="card in cards"
            :key="card.title"
          >
            <v-card :class="`rounded-lg`">
              <v-img
                :src="card.src"
                class="white--text align-end"
                gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                height="200px"
              >
              </v-img>
              <v-card-subtitle
                v-text="card.text"
                class="ml-4"
              ></v-card-subtitle>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-card>
  </div>
</template>

<script>
export default {
  data: () => ({
    cards: [
      {
        src: "p1.png",
        flex: 4,
        text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. ",
      },
      {
        src: "p2.png",
        flex: 4,
        text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. ",
      },
      {
        src: "3.png",
        flex: 4,
        text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. ",
      },
      {
        src: "p4.png",
        flex: 4,
        text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. ",
      },
      {
        src: "p5.png",
        flex: 4,
        text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. ",
      },
      {
        src: "p6.png",
        flex: 4,
        text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. ",
      },
    ],
  }),
};
</script>

<style>
</style>