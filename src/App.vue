<template>
  <v-app>
    <v-container>
      <v-row class="justify-center">
        <Sidebar class="col-3" style="background-color:#189AB4" />
        <Body class="col-7" style="background-color:#D4F1F4"  />
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
import Sidebar from "./components/sidebar";
import Body from "./components/body";

export default {
  name: "App",

  components: {
    Sidebar,
    Body,
  },

  data: () => ({
    //
  }),
};
</script>
