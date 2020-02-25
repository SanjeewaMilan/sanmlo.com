<template>
  <div class="SideBar">
    <div class="logo">
      <img src="../assets/san-mlo-logo.png" alt="" width='45%'>
    </div>
    <div>
      <b-nav vertical class="w-25">
        <b-nav-item >Active</b-nav-item>
        <b-nav-item>Link</b-nav-item>
        <b-nav-item>Another Link</b-nav-item>
        <b-nav-item >Disabled</b-nav-item>
      </b-nav>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SideBar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.SideBar{
  background:#141E30;
  color:white;
  height:98vh;
  border-color: white;
  border-right-style: solid;
   border-width:1px;
}
.nav-item a{
  color:white;
}
</style>
