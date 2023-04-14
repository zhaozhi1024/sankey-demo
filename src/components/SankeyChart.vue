<!--
 * @Author: 赵志
 * @Date: 2023-04-14 13:56:00
 * @LastEditTime: 2023-04-14 15:40:32
 * @LastEditors: 赵志
 * @Description: 
-->
<template>
  <div class="chart" ref="div"></div>
</template>

<script>
import { showDemoSankey } from "sankey-with-source";

export default {
  name: "SankeyChart",
  mounted() {
    showDemoSankey(this.$refs.div);
  },
};
</script>

<style scoped>
@import "sankey-with-source/style/sankey.css";

.chart {
  width: calc(100% - 200px);
  margin-left: 100px;
  height: 600px;
  border: 1px solid gray;
}
</style>