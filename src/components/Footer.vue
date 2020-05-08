<template>
  <footer>
    <p>{{ footerText }}</p>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      footerText: "2020!!"
    };
  }
};
</script>

<style lang="scss" scoped>
@import "./src/scss/variables.scss";
footer {
  background-color: map-get($colors, colors1);

  height: 40px;
  display: flex;
  justify-content: center;
}
p {
  color: map-get($colors, colors3);
  margin: 0;
  display: flex;
  align-items: center;
}
</style>