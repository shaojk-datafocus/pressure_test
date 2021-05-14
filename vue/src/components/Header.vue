<template>
  <div>
    <a>首页</a>
    <a>采购订单</a>
    <a>库存查询</a>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
div{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
a{
    font-size: 20px;
    padding: 20px 10px;
    color: white;
    background: green;
    border-radius: 5px;
    border: 1px ;
}
</style>