<template>
    <div>
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">
  <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#" style="font-size:15px;">Welcome<br>Sandeep Sharma</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav >
      <b-navbar-nav >
        <b-nav-item href="#" active><i class="fa fa-cog"></i> Subject</b-nav-item>
        <b-nav-item href="#" active><i class="fa fa-cog"></i> Topics</b-nav-item>
        <b-nav-item href="#" active><i class="fa fa-cog"></i> Questions</b-nav-item>
        <i class="fa fa-wrench" style="color:white; padding-top :11px; padding-right:0px;" ></i><b-nav-item-dropdown text="Utilities" >
          <b-dropdown-item href="#" >EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
          <b-dropdown-item href="#">RU</b-dropdown-item>
          <b-dropdown-item href="#">FA</b-dropdown-item>
        </b-nav-item-dropdown>
        
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <i class="fa fa-bars" style="color:white; padding-top :11px; padding-right:0px;" ></i>
        <b-nav-item-dropdown text="Pages" text-color="white">
          <b-dropdown-item href="#" >EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
          <b-dropdown-item href="#">RU</b-dropdown-item>
          <b-dropdown-item href="#">FA</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item href="#" active><i class="fa fa-chart-line"> Charts</i></b-nav-item>
        <b-nav-item href="#" active><i class="fa fa-table"> Tables</i></b-nav-item>
      </b-navbar-nav>
    </b-collapse>
</b-navbar>
        <!-- The second part including the search ang logout-->
        <br><hr><br>

    
    <div>
  <b-navbar toggleable="lg" type="dark" variant="secondary" style="color:white;padding:4px;">
    <b-nav-form>
          <b-form-input size="sm" class="mr-sm-2" placeholder="Search for"></b-form-input>
    </b-nav-form>
  

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto" style="padding-top:4px;">
        <a href="#"><i class="fa fa-bell" style="color:white; padding:5px; size:9px;"></i></a>
        <a href="#"><i class="fa fa-envelope" style="color:white; padding:5px; size : 9px;"></i></a>
        <h6 style="padding:5px;">Sandeep</h6>
        <a href="#" style="color:white; text-decoration:none;"><h6 style="padding:5px;">LogOut</h6></a>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>

</div>




</template>

<script>

</script>


<style scoped>

</style>
