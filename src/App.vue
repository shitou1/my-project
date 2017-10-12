<template>
  <div id="app">
    <mt-tab-container class="page-tabbar-container" v-model="selected">
      <mt-tab-container-item id="外卖">
        餐厅
      </mt-tab-container-item>
      <mt-tab-container-item id="订单">
        订单
      </mt-tab-container-item>
      <mt-tab-container-item id="发现">
        发现
      </mt-tab-container-item>
      <mt-tab-container-item id="我的">
        我的
      </mt-tab-container-item>
    </mt-tab-container>
    <mt-tabbar v-model="selected" fixed>
      <mt-tab-item id="外卖">
        外卖
      </mt-tab-item>
      <mt-tab-item id="订单">
        订单
      </mt-tab-item>
      <mt-tab-item id="发现">
        发现
      </mt-tab-item>
      <mt-tab-item id="我的">
        我的
      </mt-tab-item>
    </mt-tabbar>
  </div>
</template>

<script>

  export default {
    name: 'app',
    data() {
      return {
        selected: '外卖'
      }
    }
  }
</script>
