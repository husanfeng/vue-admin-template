<template>
  <div class="dashboard-container">
    <div class="dashboard-top">
      <!-- <broken-line-chart /> -->
      <div class="left">
        <p class="p1">华润医药商业</p>
        <p class="p2">让数据成为生产力！</p>
      </div>
      <div class="center">
        <span>润药商城</span>
        <span>订货会小程序</span>
        <span>ERP</span>
      </div>
      <div class="right" />
    </div>
  </div>
</template>

<script>
// import { mapGetters } from 'vuex'
// import { BrokenLineChart } from '@/components/Charts/BrokenLineChart/index.vue'
// import { BrokenLineChart } from '../../components/Charts/BrokenLineChart/index'
export default {
  name: 'Dashboard',
  components: {
    // BrokenLineChart
  }
  // computed: {
  //   ...mapGetters([
  //     'name'
  //   ])
  // }
}
</script>

<style scoped>
.dashboard-container {
}
.dashboard-top {
  color: #ffffff;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
.dashboard-top .p1 {
  font-weight: 500;
  font-size: 20px;
  margin-left: 50px;
}
.dashboard-top .p2 {
  margin-left: 30px;
  color: rgb(193, 195, 197);
  margin-top: 23px;
}
.left {
  display: flex;
  flex: 1;
  align-items: center;
}
.center {
  flex: 1;
  display: flex;
  justify-content: space-around;
}

.center span {
  width: 33%;
  text-align: center;
  border: 0;
  background: url("../../assets/form.png") no-repeat;
  width: 178px;
  background-position: center;
  height: 76px;
  background-size: contain;
  line-height: 76px;
}
.right {
  flex: 1;
}
</style>
