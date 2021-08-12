<template>
  <div class="mainContent">
    <div class="wei">
      请输入需摇号中学:
      <input type="text" placeholder="请输入需摇号中学">
      请输入录取人数:
      <input type="text" placeholder="请输入录取人数">
      请输入每次抽取人数:
      <input type="text" placeholder="请输入每次抽取人数">
    </div>
    <div class="box3">
      <table class="lebt" border="1" width="1000" >
        <tr width="250px">
          <th width="250px">姓名</th>
          <th width="250px">性别</th>
          <th width="250px">身份证</th>
          <th width="250px">报名中学</th>
        </tr>
        <tr>
          <td>杨漱玉</td>
          <td>女</td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td>谢墨岚</td>
          <td>男</td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td>柳阮阮</td>
          <td>女</td>
          <td></td>
          <td></td>
        </tr>
        <tr>
          <td>赫连年</td>
          <td>男</td>
          <td></td>
          <td></td>
        </tr>
      </table>
    </div>
    <div class="box4"></div>
      <a href=""  class="d2">
        <span>开始摇号</span>
      </a>
    <div class="box5"></div>
    <span class="fontShow">目前抽取第xx次</span><br>
    <span class="fontShow">已经抽取xx人</span>
  </div>
</template>

<script>
export default {
  name: 'MainContent',
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.mainContent{
  width: auto;
  height: 700px;
  background-color: #ffffff;
}
table,table tr th, table tr td { border:1px solid #000000; }
table {line-height: 50px; text-align: center; border-collapse: collapse; padding:2px;}

.lebt {
  position: absolute;
  left: 380px;
  bottom: 300px;
}
.wei{
  margin-top: 50px;
}
.d2{
  background:#5994CE;
  border:1px;
  text-decoration:none;
  display:inline-block;
  padding: 16px 70px;
  border-radius:5px;
}
a.d2 span {
  font-weight:bold;
  color:#f3f0e2;
}
.box4{
  height: 1px;
  background-color:#ffffff;
  padding-top: 350px;
}
.box5{
  height: 1px;
  background-color:#ffffff;
  padding-top: 10px;
}
.fontShow{
  font-size: 20px;text-stroke: 2px #2c9cf0;

  font-weight: bold;
  padding-right: 1000px;
}
</style>
