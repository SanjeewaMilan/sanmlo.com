<template>
  <div class="MainWindow">
    <div class='row content align-items-center'>
      <div class="col-md-7">
        <div class="title">
            <H1>Skills !!</H1>

        </div>
      </div>
      <!--Logo-->
      <div class="col-md-5">
        
      </div>
      <!--end of Logo-->
    </div>
  </div>
</template>

<script>
export default {
  name: 'Skills',
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
