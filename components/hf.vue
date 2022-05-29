<template>
  <div>
    <v-container class="d-flex justify-end">
      
    <v-slide-group
      multiple
      show-arrows
    >
    <v-slide-item>
      <NuxtLink to="/">
        <v-btn text> Home </v-btn>
      </NuxtLink>
    </v-slide-item>
    <v-slide-item>
      <NuxtLink to="/about">
        <v-btn text> About US </v-btn>
      </NuxtLink>
    </v-slide-item>
    <v-slide-item>
      <NuxtLink to="/service">
        <v-btn text> Services </v-btn>
      </NuxtLink>
    </v-slide-item>
      <NuxtLink to="/career">
      <v-btn text> Career </v-btn>
      </NuxtLink>
      <v-slide-item>
      <NuxtLink to="/contact">
      <v-btn text> Contact Us </v-btn>
      </NuxtLink>
      </v-slide-item>
    </v-slide-group>
    </v-container>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>