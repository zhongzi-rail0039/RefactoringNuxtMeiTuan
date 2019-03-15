<template>
  <el-container class="layout-default">
    <el-header>
      <my-header/>
    </el-header>
    <el-main>
      <nuxt/>
    </el-main>
    <el-footer>Footer</el-footer>
  </el-container>
</template>

<script type="text/javascript">
import MyHeader from '@/components/public/header/index.vue';
export default {
  data() {
    return {}
  },
  components: {
    MyHeader
  }
}
</script>


<style>
</style>
