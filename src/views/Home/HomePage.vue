<template>
  <div>
    <AppBar />
    <HeaderSection />
  </div>
</template>

<script>
import AppBar from "../../components/AppBar/AppBar.vue";
import HeaderSection from "../../components/HeaderSection/HeaderSection.vue";

export default {
  name: "HomePage",

  components: {
    AppBar,
    HeaderSection,
  },

  data: () => ({
    //
  }),
};
</script>
