<template>
  <div id="main">
    
  <img alt="Vue logo" src="./assets/logo.png">
  <img alt="Vue logo" src="./assets/logo.png">
  <img alt="Vue logo" src="./assets/logo.png">
  <img alt="Vue logo" src="./assets/logo.png">
  <img alt="Vue logo" src="./assets/logo.png">
  <img alt="Vue logo" src="./assets/logo.png">
</div>
  <HelloWorld msg="I am Welcome to myself in very buatifull and Sweet VueJs Course "/>
  <InterpolationAndData/>
  <MethodDefineUse/>
  <VueJsEvent/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import InterpolationAndData from './components/InterpolationAndData.vue';
import MethodDefineUse from './components/MethodDefineUse.vue';
import VueJsEvent from './components/VueJsEvent.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    InterpolationAndData,
    MethodDefineUse,
    VueJsEvent,
  }
}
</script>

<style scoped>
#main{
  background-color: bisque;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: green;
  margin-top: 1px;
}
</style>
