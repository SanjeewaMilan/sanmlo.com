<template>
  <div class="SideBar">
    <div class="logo">
      <img src="../assets/san-mlo-logo.png" alt="" width='45%'>
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
  background:#243B55;
  color:white;
  height:98vh;
}
</style>
