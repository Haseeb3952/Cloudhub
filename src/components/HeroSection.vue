<template>
  <div class="container position-relative home-section">
    <div class="row">
      <div class="col-12">
        <h1
          class="fw-bold main-heading mt-lg-5 mt-3 text-dark text-lg-center text-start"
        >
          Create, inspect, and apply <span class="divider"></span>
          synthetic surveillance broadly.
        </h1>
        <p class="mt-3 text-lg-center text-start">
          Start with a stunning homepage. Stay motivated without hurting your
          pocket.
        </p>
        <div
          class="d-flex justify-content-lg-center justify-content-start align-items-center"
        >
          <button class="btn bg-orange rounded-pill text-white">
            Start for free
          </button>
        </div>
        <p class="text-light-dark mt-4 text-center">
          Want to talk or get a live demo?
          <a href="#" class="text-dark text-decoration-none fw-bold">
            Get in touch <i class="fa-solid fa-arrow-right"></i>
          </a>
        </p>
        <img
          src="../assets/Hero-Background-img.png"
          alt="Hero Background"
          class="img-fluid w-100 position-absolute hero-img"
        />
      </div>
    </div>
  </div>
</template>

<style scoped>
.bg-orange {
  background-color: #ff591e;
}
.bg-orange:hover {
  background-color: #fb432c;
}

.text-light-dark {
  color: #a3a3a3;
}

.home-section {
  z-index: 100;
}

.hero-img {
  top: 100px;
  right: 0px;
  z-index: -1;
  overflow-x: hidden;
}

.main-heading {
  font-size: 50px;
}

@media (max-width: 767px) {
  .hero-img {
    top: 280px;
  }
  .main-heading {
    font-size: 30px;
  }
  .divider {
    display: none;
  }
}

@media (min-width: 768px) {
  .divider {
    display: block;
    visibility: hidden;
    font-size: 0;
  }
}
</style>
