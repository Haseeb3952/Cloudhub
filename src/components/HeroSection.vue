<template>
  <div>
    <div class="container position-relative">
      <div class="row">
        <div class="col-12">
          <h1 class="fw-bold mt-4 text-dark text-center">
            Create, inspect, and apply <span class="divider"></span>
            synthetic surveillance broadly.
          </h1>
          <p class="mt-3 text-center">
            Start with a stunning homepage. Stay motivated without hurting your
            pocket.
          </p>
          <div class="d-flex justify-content-center align-items-center">
            <button class="btn bg-orange rounded-pill text-white">
              Start for free
            </button>
          </div>
          <p class="text-light-dark mt-4 text-center">
            Want to talk or get a live demo?
            <a href="#" class="text-dark text-decoration-none fw-bold"
              >Get in touch <i class="fa-solid fa-arrow-right"></i
            ></a>
          </p>
          <img
            src="../assets/Frame-1.svg"
            alt="Frame"
            class="img-fluid w-100 position-absolute hero-img"
          />
        </div>
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
.hero-img {
  top: 10px;
}
@media (max-width: 767px) {
  .hero-img {
    top: 280px;
  }
  .divider {
    display: none;
  }
}
@media (min-width: 767.98px) {
  .divider {
    display: block;
    visibility: hidden;
    font-size: 0;
  }
}
</style>
