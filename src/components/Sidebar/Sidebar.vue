<template>
  <div class="side-menu"></div>
</template>

<script>
export default {
  name: "App",

  components: {
    //
  },
  data: () => ({
    items: [
      { text: "Real-Time", icon: "mdi-clock" },
      { text: "Audience", icon: "mdi-account" },
      { text: "Conversions", icon: "mdi-flag" },
    ],
  }),
};
</script>

<style>
.side-menu {
  position: absolute;
  left: 0;
  top: 0;
  bottom: 0;
  width: 20rem;
  background: red;
}
</style>
