<template>
<HeaderApp/>
  <router-view/>
<FooterApp/>
</template>
<script>
import HeaderApp from "./components/HeaderApp.vue";
import FooterApp from "./components/FooterApp.vue";

export default{
  components:{
    HeaderApp,
    FooterApp,
  }
}
</script>



<style lang="scss">
*{box-sizing: border-box;}
body {
  margin: 0 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
