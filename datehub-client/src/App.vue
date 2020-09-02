<template>
  <v-app>
    <AppBar/>

    <v-main>
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<script>
import AppBar from './components/TheAppBar';
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    AppBar,
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
