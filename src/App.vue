<template>
  <div id="app">
    <M-NavigationBar></M-NavigationBar>
    <router-view/>
  </div>
</template>

<script>
import MNavigationBar from "./components/M-NavigationBar/M-NavigationBar";

export default {
  components: {
    MNavigationBar
  }
};
</script>
<style lang="sass">

html, body
  padding: 0
  margin: 0

#app
  font-family: "Avenir", Helvetica, Arial, sans-serif
  -webkit-font-smoothing: antialiased
  -moz-osx-font-smoothing: grayscale
  text-align: center
  color: #151d28

</style>
