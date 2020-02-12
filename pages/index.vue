<template>
  <v-layout
    column
    justify-center
    align-center
  >

    <v-container fluid>
      <v-row dense>
        <v-col>
          <v-card>
          <v-card-title class="mushroom-tracker">
          Mushroom Tracker
        </v-card-title>
          <v-img
              :src="require('@/assets/images/mushrooms.jpg')"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              title="Mushroom Tracker"
              width="550"
            >
            </v-img>
            <v-card-actions>
              <v-spacer></v-spacer>
              
            </v-card-actions>
          </v-card>
        </v-col>
                <v-col>
          <v-card>
          <v-card-title class="mushroom-tracker">
          Mushroom Tracker
        </v-card-title>
          <v-img
              :src="require('@/assets/images/mushrooms.jpg')"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              title="Mushroom Tracker"
              width="550px"
            >
            </v-img>
            <v-card-actions>
              <v-spacer></v-spacer>
              
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
    </v-container>

    <v-flex
      xs12
      sm8
      md3
    >
      <div class="text-center">
        <logo />
        <vuetify-logo />
      </div>
      <v-card>
        <v-card-title class="headline">
          Welcome to the Vuetify + Nuxt.js template
        </v-card-title>
        <v-card-text>
          <p>Vuetify is a progressive Material Design component framework for Vue.js. It was designed to empower developers to create amazing applications.</p>
          <p>
            For more information on Vuetify, check out the <a
              href="https://vuetifyjs.com"
              target="_blank"
            >
              documentation
            </a>.
          </p>
          <p>
            If you have questions, please join the official <a
              href="https://chat.vuetifyjs.com/"
              target="_blank"
              title="chat"
            >
              discord
            </a>.
          </p>
          <p>
            Find a bug? Report it on the github <a
              href="https://github.com/vuetifyjs/vuetify/issues"
              target="_blank"
              title="contribute"
            >
              issue board
            </a>.
          </p>
          <p>Thank you for developing with Vuetify and I look forward to bringing more exciting features in the future.</p>
          <div class="text-xs-right">
            <em><small>&mdash; John Leider</small></em>
          </div>
          <hr class="my-3">
          <a
            href="https://nuxtjs.org/"
            target="_blank"
          >
            Nuxt Documentation
          </a>
          <br>
          <a
            href="https://github.com/nuxt/nuxt.js"
            target="_blank"
          >
            Nuxt GitHub
          </a>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn
            color="primary"
            nuxt
            to="/inspire"
          >
            Continue
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>

<style>

  #main {
    color: green;
    font-size:32px;
    width:50vw;
  }

  .table-overflow {
    max-height: 65vh;
    overflow-y:scroll;
    clear: both;
  }

  #delivery-hold-queue-table {
    font-family: 'Trebuchet MS', Arial, Helvetica, sans-serif;
    font-size: 16px;
    border-collapse: collapse;
    width: 100%;
    margin-top: 20px;
  }

</style>
