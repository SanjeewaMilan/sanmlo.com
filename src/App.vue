<template>
  <div id="app">
    <div class='row no-gutters'>
      <div class='col-sm-12 col-md-3 col-lg-2'>
        <SideBar></SideBar>
      </div><!--/.col-md-4-->
      <div class='col-sm-12 col-md-9 col-lg-10'>
        <MainWindow></MainWindow>
      </div><!--/.col-md-8-->
    </div><!--/.row-->
    
  </div>
</template>

<script>
import SideBar from './components/SideBar.vue'
import MainWindow from './components/MainWindow.vue'

export default {
  name: 'App',
  components: {
    SideBar,
    MainWindow
  }
}
</script>

<style lang="scss">

@font-face {
  font-family: sans-serif;
  src: url(../assets/FredokaOne-Regular.ttf);
}

</style>
