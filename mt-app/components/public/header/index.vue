<template>
  <el-row class="m-header">
    <el-col :span="6">
      <geo/>
    </el-col>
    <el-col :span="6">

    </el-col>
    <el-col :span="6">

    </el-col>
  </el-row>
</template>

<script>
  import Geo from './geo.vue'

  export default {
    components: {Geo}
  }
</script>

<style lang='scss'>
  @import "@/assets/css/public/layout.scss";
</style>
