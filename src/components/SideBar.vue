<template>
  <div class="sideBar">
    <h3></h3>
      <div class="box4"></div>
      <a href=""  class="d2">
      <span>导入表格</span>
      </a>
      <div class="box4"></div>
      <a href=""  class="d2">
        <span>导出表格</span>
      </a>
    <div class="search">
      <input type="text" placeholder="请输入要查询学生学号" name="" id="" value="" />
      <button>搜索</button>
    </div>

  </div>

</template>

<script>
export default {
  name: 'SideBar',
mounted() {
      //使用axios发送ajax请求
}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.sideBar{
  width: 239px;
  height: 1000px;
  background-color: #BEDAFA;
  float: left;
  font-family:黑体;
}

.d2{
  background:#5994CE;
  border:1px;
  text-decoration:none;
  display:inline-block;
  padding: 30px 86px;
  border-radius:5px;
}
a.d2 span {
  font-weight:bold;
  color:#f3f0e2;
}
.box4{
  height: 1px;
  background-color:#BEDAFA;
  padding-top: 0.5px;
  clear: left;/* 清除左侧浮动：box3的左侧不允许有浮动元素 */
}



</style>
