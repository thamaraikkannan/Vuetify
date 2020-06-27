<template>
  <v-app>
    <navType/>
    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import navType from './components/nav';
export default {
  name: 'App',

  components: {
    HelloWorld,
    navType,
  },

  data: () => ({
    //
  }),
};
</script>
