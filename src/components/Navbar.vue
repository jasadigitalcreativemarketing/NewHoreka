<template>
  <div class="Navbar">
    <!-- Start Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light fixed-top">
      <div class="container">
        <a class="navbar-brand" href="#">Horeka</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <div class="input-group input-style">
            <div class="input-group-prepend">
              <button class="btn dropdown-toggle dropdown-style" type="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">All</button>
              <div class="dropdown-menu">
                <a class="dropdown-item" href="#">item</a>
                <a class="dropdown-item" href="#">item</a>
                <a class="dropdown-item" href="#">item</a>
                <div role="separator" class="dropdown-divider"></div>
                <a class="dropdown-item" href="#">item</a>
                <a class="dropdown-item" href="#">item</a>
                <a class="dropdown-item" href="#">item</a>
              </div>
            </div>
            <input type="search" class="form-control form-style" aria-label="search item" placeholder="what are you looking for....">
            <div class="input-group-append">
              <button class="btn btn-group-text btn-group-style bg-main text-white" type="button" id="button-addon2">SEARCH</button>
            </div>
          </div>
          <div class="navbar-nav">
            <a class="nav-item nav-link" href="#"><i class="fa fa-list-alt fa-2x"></i><span class="align-top text-style">DAILY MARKET LIST</span></a>
            <a class="nav-item nav-link" href="#"><i class="fa fa-search fa-2x" aria-hidden="true"></i></a>
            <a class="nav-item nav-link" href="#"><i class="fa fa-shopping-cart fa-2x" aria-hidden="true"></i></a>
          </div>
          <div class="btn-group" role="group" aria-label="Basic example">
            <button @click="$router.push('/')"  type="button" class="btn btn-register text-center">REGISTER</button>
            <button @click="$router.push('about')" type="button" class="btn btn-login text-center">LOGIN</button>
          </div>
        </div>
      </div>
    </nav>
    <!-- End Navbar -->
  </div>
</template>

<script>
export default {
  name: 'Navbar',
}
</script>
