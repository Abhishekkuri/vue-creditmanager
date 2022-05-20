<template>
  <div id="app">
    <div class="home">
      <img alt="Vue logo" src="./assets/logo.png" class="visma-logo" />
    </div>
    <navigation-item />
    <router-view />
    <page-footer class="page-footer" />
  </div>
</template>

<script>
import NavigationItem from "./components/NavigationItem.vue";
import PageFooter from "./components/PageFooter.vue";
export default {
  components: { NavigationItem, PageFooter },
};
</script>

<style lang="scss">
html,
body {
  box-sizing: border-box;
  margin: 0px !important;
  padding: 0 !important;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}

.visma-logo {
  height: 2rem;
  padding: 2rem;
}
</style>
