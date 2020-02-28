<template>
  <div class="MainWindow">
    <div class=''>

    </div>
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
</style>
