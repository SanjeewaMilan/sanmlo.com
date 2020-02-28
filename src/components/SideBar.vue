<template>
  <div class="SideBar">
    <div class="logo d-flex justify-content-center pt-3">
      <img src="../assets/san-mlo-logo.png" alt="" width='40%'>
    </div>
    <div class="nav-links d-flex justify-content-center">
      <div class="d-flex  align-self-center">
        <b-nav vertical>
          <b-nav-item><font-awesome-icon icon="home" /> Welcome</b-nav-item>
          <b-nav-item><font-awesome-icon icon="user-circle" /> About Me</b-nav-item>
          <b-nav-item><font-awesome-icon icon="biking" /> Skills</b-nav-item>
          <b-nav-item><font-awesome-icon icon="images" /> Portfolio</b-nav-item>
          <b-nav-item><font-awesome-icon icon="book" /> Blog</b-nav-item>
          <b-nav-item><font-awesome-icon icon="envelope" /> Contact Me</b-nav-item>
        </b-nav>
      </div>
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

@font-face {
  font-family: Arial, Helvetica, sans-serif;
  src: url(../../assets/FredokaOne-Regular.ttf);
}

.SideBar{
  background:#141E30;
  color:white;
  height:100vh;
  border-color: white;
  border-right-style: solid;
   border-width:1px;
}

.nav-links{
  height:70vh;
}
.nav-item a{
  color:white;
}

</style>
