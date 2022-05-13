<template>
      <v-app-bar
        color="#E6E5E3"
      >
        <template v-slot:prepend>
          <v-app-bar-nav-icon></v-app-bar-nav-icon>
        </template>

        <v-spacer></v-spacer>
      </v-app-bar>
</template>

<script>
export default {
  name: "AppBar",

  data: () => ({
    //
  }),
};
</script>
