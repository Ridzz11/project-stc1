<template>
  <div class="d-flex justify-content-center m-2">
    <div class="row">
      <div class="col-2 align-top pt-1">
        <img src="../assets/logo.png" alt="" />
      </div>
      <!-- <div class="col pt-2">
        <h5>SAVE THE CHILDREN</h5>
        <h8>Jl.Bangka IX No.40AB Kota Jakarta Selatan</h8>
      </div> -->
    </div>
  </div>
  <nav
    class="navbar navbar-expand-lg navbar-light shadow py-4 d-flex justify-content-center"
  >
    <div class="c">
      <butto
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNavDropdown"
        aria-controls="navbarNavDropdown"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </butto>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <nuxt-link to="/">
            <li class="nav-item">
              <a class="nav-link" href="#">BERANDA</a>
            </li>
          </nuxt-link>
          <nuxt-link to="/galeri">
            <li class="nav-item">
              <a class="nav-link" href="#">GALERI</a>
            </li>
          </nuxt-link>
        </ul>
      </div>
    </div>
  </nav>
</template>
<style scoped>
img {
  height: 65px;
  margin-left: 9px;
}

li {
  font-family: sans-serif;
}
* {
  text-decoration: none;
  color: black;
}

.navbar {
  position: sticky;
  top: 0;
  background-color: white;
  z-index: 1;
}
</style>
