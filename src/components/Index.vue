<template>
  <div class="index">
    <Header/>
    <SideBar/>
    <MainContent/>
  </div>
</template>

<script>
  import Header from "./Header";
  import SideBar from "./SideBar";
  import MainContent from "./MainContent";
export default {
  name: 'Index',
    components: {Header,
        SideBar,
        MainContent}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .index{
    margin: 0;
    padding: 0;
  }
</style>
