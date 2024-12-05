<template>
  <div id="app">
    <h1>Hello, Vue!</h1>
    <el-button type="primary">点击我</el-button>
  </div>
</template>

<script>
import { ElButton } from 'element-plus';

export default {
  name: 'App',
  components: {
    ElButton
  }
}
</script>

<style>
@import 'element-plus/dist/index.css';
</style>
