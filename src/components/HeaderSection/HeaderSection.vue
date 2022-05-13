<template>
  <div class="header-background"></div>
</template>

<script>
export default {
  name: "HeaderSection",

  data: () => ({
    //
  }),
};
</script>

<style scoped>
.header-background {
  height: calc(100vh - 64px);
  width: 100vw;
  background: linear-gradient(45deg, rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.6)),
    url("../../assets/images/pexels-pixabay-459654.jpeg");
  background-size: 100% auto;
  background-position: center;
}
</style>
