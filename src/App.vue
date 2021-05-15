<template>
  <div id="app" class="container-fliud">
    <top style="margin-bottom: 2em"/>
    <router-view/>
  </div>
</template>

<script>
// @ is an alias to /src
import Top from './components/Top.vue';

export default {
  name: 'App',
  components: {
    Top,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 200px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
