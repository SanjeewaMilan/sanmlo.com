<template>
  <div class="MainWindow">
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'MainWindow',
  props: {
   
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
$primary:#243B55;
$secondary:#141E30;

.MainWindow {
    background:$primary;
    height: 100vh;
    background-image: radial-gradient( $primary,$secondary);
   
}
.title{
  color:white;
  padding-left:1rem;
  h1{
    font-size:3.5rem;
  }
}

.content{
  height: 100vh;
}
</style>
