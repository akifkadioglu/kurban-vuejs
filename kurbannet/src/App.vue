<template>
  <v-app>
    <v-main>
      <app-main />
    </v-main>
  </v-app>
</template>

<script>
import MainVue from "./components/Main";

export default {
  name: "App",

  components: {
    "app-main": MainVue,
  },

  data: () => ({
    //
  }),
};
</script>
