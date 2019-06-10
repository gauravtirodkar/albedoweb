<template>
  <div id="app">
     <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">
      <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#">Albedo</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#" active>Home</b-nav-item>
        <b-nav-item href="#" >Students</b-nav-item>
        <b-nav-item href="#" >Teachers</b-nav-item>
        <b-nav-item href="#" >Schools</b-nav-item>
        <b-nav-item href="#" >ContactUs</b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-form>
          <i class="fab fa-facebook-f" style="padding:5px; margin:5px;"></i>
          <i class="fab fa-instagram" style="padding:5px; margin:5px;"></i>
          <i class="fab fa-twitter" style="padding:5px; margin:5px;"></i>
          <i class="fab fa-pinterest" style="padding:5px; margin:5px;"></i>
          <button class="btn btn-success" style="padding:5px; margin:5px;">SignUp</button>
          <button class="btn btn-danger" style="padding:5px; margin:5px;">Register</button>
        </b-nav-form>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
  <b-img src="https://picsum.photos/1024/400/?image=35" fluid alt="Responsive image" style="width:100%"></b-img>
  </div>

</template>

<script>
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
h5{ 
  background: blue;
  color: wheat;
  float:left;
  width:10%;
}

</style>
