<template><!-- html代码 ，视图部分-->
  <div>
    <!-- <h1>{{ message }}</h1> -->
    <!-- <element-view></element-view> -->

    <!-- 员工管理 -->
    <emp-view></emp-view>
  </div>
</template>


<script> /* js代码 */
import EmpView from './views/tlias/EmpView.vue'
/* import ElementView from './views/element/ElementView.vue' */
export default {
  components:{EmpView/* ElementViewEmpView */},
  data() {
    return {
      message: "hello world",
    };
  },

  methods: {},
};
</script>

<style>/* css样式 */

</style>