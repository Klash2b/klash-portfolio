<template>
  <v-app>
    <v-main>
      <Header />
      <Main />
      <Footer />
    </v-main>
  </v-app>
</template>

<script>
import Header from "./components/Header";
import Main from "./components/Main";
import Footer from "./components/Footer";

export default {
  name: "App",

  components: {
    Header,
    Main,
    Footer,
  },

  data: () => ({
    //
  }),
};
</script>
