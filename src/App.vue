<template>
  <v-app>
    <Header></Header>
    <v-main>
      <Information></Information>
      <Quiz></Quiz>
    </v-main>
    <Footer></Footer>
  </v-app>
</template>

<script>
import Header from './components/Header';
import Information from './components/Information';
import Quiz from './components/Quiz.vue';
import Footer from './components/Footer';

export default {
  name: 'App',

  components: {
    Header,
    Information,
    Quiz,
    Footer,
  },

  data: () => ({}),

  created() {
    this.$vuetify.theme.dark = true;
  },
};
</script>
