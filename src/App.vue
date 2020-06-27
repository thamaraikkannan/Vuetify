<template>
  <v-app>
    <navType/>
    <headerType/>
    <v-content>
      <index/>
    </v-content>
    <footerType/>
  </v-app>
</template>

<script>
import index from './components/index';
import navType from './components/nav';
import headerType from './components/header';
import footerType from './components/footer';
export default {
  name: 'App',

  components: {
    index,
    navType,
    headerType,
    footerType,
  },

  data: () => ({
    //
  }),
};
</script>
