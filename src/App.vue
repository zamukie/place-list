<template>
  <v-app>
    <Navbar />
    <v-main>
      <test/>
    </v-main>
  </v-app>
</template>

<script>
import Navbar from './components/Navbar.vue'
import test from './components/test.vue'

export default {
  name: 'App',

  components: {
    Navbar,
    test
  },

  data: () => ({
    //
  }),
};
</script>
