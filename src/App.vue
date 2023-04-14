<!--
 * @Author: 赵志
 * @Date: 2023-04-14 13:53:19
 * @LastEditTime: 2023-04-14 15:47:19
 * @LastEditors: 赵志
 * @Description: 
-->
<template>
  <div>
    <SankeyChart2 />
    <!-- <SankeyChart /> -->
  </div>
</template>

<script>
// import SankeyChart from './components/SankeyChart.vue'
import SankeyChart2 from './components/SankeyChart2.vue'

export default {
  name: 'App',
  components: {
    // SankeyChart,
    SankeyChart2
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
