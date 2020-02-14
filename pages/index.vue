<template>
  <v-layout column justify-center align-center>
    <v-container fluid>
      <v-row dense>
        <v-col>
          <v-card>
            <v-card-title class="mushroom-tracker"
              >Mushroom Tracker</v-card-title
            >
            <nuxt-link
              :src="mushrooms"
              tag="img"
              to="/mushrooms"
              width="550"
              height="300"
            ></nuxt-link>
            <v-card-actions>
              <v-spacer />
              <v-btn color="primary" nuxt to="/mushrooms">Continue</v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col>
          <v-card>
            <v-card-title class="plant-tracker">Plant Tracker</v-card-title>
            <nuxt-link
              :src="plants"
              tag="img"
              to="/plants"
              width="550"
              height="300"
            ></nuxt-link>
            <v-card-actions>
              <v-spacer />
              <v-btn color="primary" nuxt to="/plants">Continue</v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </v-layout>
</template>

<script>
import plants from "@/assets/images/plants.jpeg";
import mushrooms from "@/assets/images/mushrooms.jpg";

export default {
  data() {
    return {
      plants: plants,
      mushrooms: mushrooms
    };
  }
};
</script>

<style>
img:hover {
  cursor: pointer;
}
</style>
