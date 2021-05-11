<template>
  <v-app>
    <v-container class="d-flex justify-center">
      <v-row class=" d-flex justify-center col-lg-10" >
        <Sidebar class="col-lg-3" style="background-color:#274472" />
        <Body class="col-lg-8" style="background-color:#e4f3f7"  />
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
