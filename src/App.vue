<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <HelloWorld/>
    <!-- 要想使用某个组件，要在这里引入页面 -->
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'//要在这里导入组件

export default {
  // name: 'App',
  components: {HelloWorld},
  setup(){
    // vue3的生命周期函数，可以按需导入到组件中
    // 且只能在 setup() 函数中使用
  }
};
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
