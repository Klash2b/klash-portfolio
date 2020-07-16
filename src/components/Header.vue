<template>
    <v-app-bar dark>
      <v-toolbar-title>Mathieu Mattei</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn text>
        Portfolio
      </v-btn>

      <v-btn text>
        À propos
      </v-btn>

      <v-btn text>
        Coordonnées
      </v-btn>

      <v-btn text>
        Contact
      </v-btn>
    </v-app-bar>
</template>

<script>
export default {
  data: () => ({
    items: [
      { title: "Click Me" },
      { title: "Click Me" },
      { title: "Click Me" },
      { title: "Click Me 2" },
    ],
  }),
};
</script>

<style scoped></style>
