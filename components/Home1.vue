<template>
  <div>
    <!-- <v-card img="home.png" height="600px"> </v-card> -->
    <v-img src="home.png"></v-img>
    <v-card class="pt-14" elevation="0">
      <v-container >
        <v-row>
          <v-col cols="12" lg="6" md="12" sm="12">
            <v-card-title class="mb-4">
              <h2>About Our Company</h2>
            </v-card-title>
            <v-card-subtitle>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Reprehenderit maxime omnis impedit repellat aspernatur dolore
              facere obcaecati esse quae quasi incidunt, neque eligendi iusto.
              Odio aperiam obcaecati dolores praesentium accusamus! Lorem ipsum
              dolor sit amet consectetur adipisicing elit. Quo ullam facere
              eaque? Deserunt vel corporis illum? Sunt alias ea laborum repellat
              sit enim molestias soluta illo ratione dolore. Voluptatibus,
              numquam. Lorem, ipsum dolor sit amet consectetur adipisicing elit.
              Ut est molestias totam doloremque eos dolore molestiae, minima
              voluptatem tenetur obcaecati corporis! Odit et itaque fugit!
              Excepturi, earum. Sit, error tempora.
            </v-card-subtitle>
            <v-btn rounded dark color="black"> Read More</v-btn>
          </v-col>
          <v-col cols="12" lg="6" md="12" sm="12">
            <v-card elevation="0" class="pl-8">
              <v-row>
                <v-col lg="5" md="6" sm="6">
                  <img
                    :class="`rounded-tr-xl rounded-bl-xl`"
                    height="150px"
                    width="220"
                    src="home1.png"
                    alt=""
                  />
                  <br />
                  <img
                    :class="`rounded-tr-xl rounded-bl-xl`"
                    height="150px"
                    width="220"
                    src="home3.png"
                    alt=""
                  />
                </v-col>
                <v-col cols="12" lg="6" md="6" sm="6">
                  <img
                    :class="`rounded-tr-xl rounded-bl-xl`"
                    height="150px"
                    width="220"
                    src="home2.png"
                    alt="" />
                  <br />
                  <img
                    :class="`rounded-tr-xl rounded-bl-xl`"
                    height="150px"
                    width="220"
                    src="home4.png"
                    alt=""
                /></v-col>
              </v-row>
            </v-card>
          </v-col>
        </v-row>

        <v-card-title>
          <h2>Our Services</h2>
        </v-card-title>

        <v-row >
          <v-col cols="12" lg="4" md="12" sm="12">
            <v-card :class="`rounded-xl`">
              <img src="card1.png" alt="" height="150" />
              <v-container>
                <h4>Website Development</h4>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                Aperiam expedita beatae est cupiditate quae eos voluptatum eum,
              </v-container>
            </v-card>
          </v-col>
          <v-col cols="12" lg="4" md="12" sm="12">
            <v-card :class="`rounded-xl`">
              <img src="card2.png" alt="" height="150" />
              <v-container>
                <h4>Application Development</h4>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                Aperiam expedita beatae est cupiditate quae eos voluptatum eum,
              </v-container>
            </v-card>
          </v-col>
          <v-col cols="12" lg="4" md="12" sm="12" >
            <v-card :class="`rounded-xl`">
              <img src="card3.png" alt="" height="150" />
              <v-container>
                <h4>Graphic Design</h4>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                Aperiam expedita beatae est cupiditate quae eos voluptatum eum,
              </v-container>
            </v-card>
          </v-col>
        </v-row>
            <v-container class="d-flex justify-center">
                <v-btn rounded dark color="black" > Read More</v-btn>
                </v-container>
      </v-container>
    </v-card>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>