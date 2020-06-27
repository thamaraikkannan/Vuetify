<template>
    <v-app-bar
      app
      color="green"
      dark
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
        

        <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
          width="100"
        />
      </div>

      <v-spacer></v-spacer>

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