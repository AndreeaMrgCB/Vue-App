<template>
<div>
  <Header></Header>
    <HelloWorld msg="Hello World"/>
  <Footer></Footer>  
</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Header from './components/Header';
import Footer from './components/Footer'


export default {
  name: 'App',
  components: {
    HelloWorld,
    Header,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
