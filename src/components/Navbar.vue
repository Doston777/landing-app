<template>
  <nav class="navbar navbar-expand-lg sticky-top text-white">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <img class="logo logo-sticky d-md-block"
             src="https://www.freepnglogos.com/uploads/at-t-logo/brand-new-emblem-at-t-png-logo-6.png"
             width="100" height="42" alt="Logo of company">
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
        <i class="fas fa-bars text-white"></i>
      </button>
      <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#home">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#features">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#pricing">Pricing</a>
          </li>
        </ul>
        <form class="d-flex">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-light" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>
</template>
<script>
export default {
	name: 'Navbar'
}
</script>
<style>

</style>