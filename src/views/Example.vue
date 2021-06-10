<template>  
    <!--Header-->
  <el-container>
    <Header />
  </el-container>
    <!---Nav và Main-->
  <el-container>
    <Nav />
    <el-main>
        Main
    </el-main>
  </el-container>
</template>

<script>
import Header from '../components/Header.vue'
import Nav from '../components/Nav.vue'
export default {
  components: {
    Header,
    Nav
  },
};
</script>

<style scoped>

</style>
