<template>
  <v-app>
    <v-app-bar app color="indigo darken-1 " dark >
      <v-app-bar-title class="white--text " >User Type</v-app-bar-title>
    </v-app-bar>
    <v-main class="indigo lighten-2">
     <sg-selection/>
    </v-main>
  </v-app>
</template>

<script>

import SgSelection from "@/components/sgSelection";

export default {
  name: 'App',

  components: {
    SgSelection
  },

  data: () => ({

  }),
};
</script>
