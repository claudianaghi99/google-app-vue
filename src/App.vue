<template>
<Header></Header>
<Content></Content>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Content from './components/Content.vue'

export default {
  name: 'App',
  components: {
    Header,
    Content
  }
}
</script>

<style>
*{
    margin: 0;
    padding:0;
    box-sizing: border-box;
} 
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
