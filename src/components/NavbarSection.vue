<template>
  <div class="container">
    <nav class="navbar navbar-expand-lg navbar-light py-4">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img src="../assets/logo.svg" alt="Logo" />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto ms-lg-5 mb-2 mb-lg-0">
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle fw-bold text-dark"
                href="#"
                id="navbarDropdown"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Product
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li><a class="dropdown-item" href="#">Product Name</a></li>
                <li><a class="dropdown-item" href="#">Product Name</a></li>
                <li><a class="dropdown-item" href="#">Product Name</a></li>
              </ul>
            </li>
            <li class="nav-item">
              <a
                class="nav-link fw-bold text-dark px-lg-3 px-0 active"
                aria-current="page"
                href="#"
                >Home</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link fw-bold text-dark px-lg-3 px-0" href="#"
                >Shop</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link fw-bold text-dark px-lg-3 px-0" href="#"
                >Pages</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link fw-bold text-dark px-lg-3 px-0" href="#"
                >Integrations</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link fw-bold text-dark px-lg-3 px-0" href="#"
                >Developers</a
              >
            </li>
          </ul>
          <div>
            <a href="#" class="text-dark text-decoration-none fw-bold me-3"
              >Login</a
            >
            <button class="btn bg-orange rounded-pill text-white">
              Start for free
            </button>
          </div>
        </div>
      </div>
    </nav>
  </div>
  <!-- <div class="border-bottom"></div> -->
</template>

<style scoped>
.bg-orange {
  background-color: #ff591e;
}

.bg-orange:hover {
  background-color: #fb432c;
}
/* .border-bottom {
  border-bottom: 1px solid #ff591e !important;
} */
.navbar-toggler:focus {
  box-shadow: none;
}
</style>
