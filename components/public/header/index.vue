<template>
  <el-row :gutter="0" class="m-header">
    <el-col :span="4">
      <geo/>
    </el-col>
    <el-col :span="6">
      <user/>
    </el-col>
    <el-col :span="14">
      <navbar/>
    </el-col>
  </el-row>
</template>

<script type="text/javascript">
import Geo from "./geo.vue";
import User from './user.vue';
import Navbar from './nav.vue'
export default {
  data() {
    return {};
  },
  components: {
    Geo,
    User,
    Navbar
  }
};
</script>

<style lang="scss" type='stylesheet/scss'>
.el-header {
  background-color: #f8f8f8;
  color: #999999;
  width: 100%;
  font-size: 12px;
  .m-header {
    width: 1190px;
    margin: 0 auto;
  }
}
</style>
