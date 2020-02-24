<template>
  <div id="app">
    <div class='row'>
      <div class='col-sm-4'>
        <SideBar></SideBar>
      </div><!--/.col-md-4-->
      <div class='col-sm-8'></div><!--/.col-md-8-->
    </div><!--/.row-->
    
  </div>
</template>

<script>
import SideBar from './components/SideBar.vue'

export default {
  name: 'App',
  components: {
    SideBar
  }
}
</script>

<style>

</style>
