<template>
  <v-app>
    <v-main>
      <Sidebar></Sidebar>>
    </v-main>
  </v-app>
</template>

<script>
import Sidebar from './components/Sidebar/Sidebar.vue';
export default {
  name: "App",

  components: {
    Sidebar: Sidebar,
  },

  data: () => ({
    //
  }),
};
</script>
