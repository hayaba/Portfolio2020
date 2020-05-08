<template>
  <div id="app">
    <myHeader />
    <myContent />
    <myFooter />
  </div>
</template>

<script>
import Header from "./components/Header";
import Content from "./components/Content";
import Footer from "./components/Footer";

export default {
  components: {
    myHeader: Header,
    myContent: Content,
    myFooter: Footer
  }
};
</script>

<style lang="scss">
@import "./src/scss/variables.scss";

body {
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: map-get($colors, colors1);
}
</style>
