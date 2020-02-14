<template>
  <v-layout column justify-center align-center>
    <v-container fluid>
      <v-row dense>
        <v-col>
          <v-card>
            <v-card-title class="new-strain">Add a New Strain</v-card-title>
            <v-img
              :src="require('@/assets/images/strain.jpg')"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              title="Mushroom Tracker"
              width="550"
              height="300"
            ></v-img>
            <v-card-actions>
              <v-spacer />
              <v-btn color="primary" nuxt to="/new-strain">Continue</v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col>
          <v-card>
            <v-card-title class="plant-tracker">Track Existing Strains</v-card-title>
            <v-img
              :src="require('@/assets/images/mushroom-strains.jpg')"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              title="Mushroom Tracker"
              width="550px"
              height="300"
            ></v-img>
            <v-card-actions>
              <v-spacer />
              <v-btn color="primary" nuxt to="/existing-strains">Continue</v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </v-layout>
</template>
