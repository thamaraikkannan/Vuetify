<template>
    <v-app-bar
      app
      color="black"
      dark
      flat
    >

    <v-app-bar-nav-icon>

    </v-app-bar-nav-icon>

      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
          transition="scale-transition"
          width="40"
        />

        <v-img
          :src="require('../assets/icon2.png')"
          class="my-3"
          contain
          transition="scale-transition"
          width="40"
        />
      
      <span class="mr-2">Iraa Designers</span>
      </div>

      <v-spacer></v-spacer>

      <v-icon>mdi-magnify</v-icon>

      <v-btn icon>
        <v-icon>mdi-heart</v-icon>
      </v-btn>

      <v-btn
        href="#"
        target="_blank"
        text
      >
      
      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>

        <span class="mr-2">Latest Release</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>
</template>
<script>
export default {
    name: 'navType' }
</script>