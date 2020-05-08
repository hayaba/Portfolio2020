<template>
  <header>
    <div id="logo">
      HAYA BARAKAT
      <br />MULTIMEDIA DESIGNER
    </div>

    <div id="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/contact">Contact</router-link>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "./src/scss/variables.scss";
header {
  background-color: map-get($colors, colors1);
  padding: 10px;
  display: flex;
  justify-content: space-between;
}
#logo {
  margin-left: 6px;
  padding: 4px;
  color: map-get($colors, colors2);
  font-weight: bold;
  border: solid thin map-get($colors, colors2);
}

#nav {
  align-self: center;
  margin-right: 10px;

  a {
    margin-left: 20px;
    font-weight: bold;
    color: map-get($colors, colors2);
    text-decoration: none;
    &.router-link-exact-active {
      color: map-get($colors, colors3);
    }
  }
}
</style>