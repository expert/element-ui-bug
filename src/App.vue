<template>
  <div id="app">
    <el-input v-model="input"></el-input>
  </div>
</template>

<script>


import Vue from 'vue'
import ElementUI from 'element-ui'
//import 'element-ui/lib/theme-chalk/index.css'
//import 'element-ui/packages/theme-chalk/src/index.scss'

Vue.use(ElementUI)

export default {
  name: 'app',
  data () {
    return {
      input: 'Hello1'
    }
  }
}
</script>

<style lang="scss">
$--font-path: '~element-ui/lib/theme-chalk/fonts';
@import '~element-ui/packages/theme-chalk/src/index.scss';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
