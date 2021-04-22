<template>
  <v-app>
    <v-main>
      <playground></playground>
      <v-text-field label="Teste"></v-text-field>
    </v-main>
  </v-app>
</template>

<script>
import Playground from "./components/Playground";

export default {
  name: "App",
  components: {
    Playground
  }
};
</script>

