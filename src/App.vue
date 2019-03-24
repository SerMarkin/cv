<template>
  <div id="app">
    <left-panel></left-panel>
    <router-view class="main" />
  </div>
</template>
<script>
  import leftPanel from '../src/components/left-panel'
  export default {
    name: 'home',
    components: {
      'left-panel': leftPanel
    }
  }
</script>
<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
  .main{
    height: auto;
    width: 80%;
    position: absolute;
    top: 0;
    right:0;
    font-family: Times, "Times New Roman", serif;
  }


</style>
