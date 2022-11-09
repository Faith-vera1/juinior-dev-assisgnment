<template>
  <div id="bar">
    <div id="title">{{ title }}</div>
  </div>
</template>

<script>
export default {
  name: "NavbarComponent",
  props: ["title"],
}
</script>

<style scoped>

  #bar{
    position: fixed;
    top: 0;
    left: 0;

    background-color: orangered;
    border-bottom: 1pt solid rgb(20, 20, 50);

    height: 8vh;
    width: 100vw;

  }
  #title {
    position: relative;
    float: left;
    font-weight: bold;
    font-size: 4vh;

    color: rgb(50, 50, 114);

    top: 2vh;
    left: 2vw;
  }

</style>