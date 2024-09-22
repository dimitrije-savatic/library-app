<template>
  <HeaderComp/>
  <router-view></router-view>
  <FooterComp/>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import FooterComp from './components/FooterComp.vue'
export default {
  name: 'App',
  components: {
    HeaderComp,
    FooterComp
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin: 0;
  padding: 0;
  font-size: 1rem;
  color: #e0fbfc;
}
body{
  margin: 0;
}
.active{
  color: #ee6c4d;
}
.wrapper{
  min-height: 88vh;
  width: 100%;
  background-color: #e0fbfc;
  display: flex;
}
</style>
