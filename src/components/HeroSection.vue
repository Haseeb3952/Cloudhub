<template>
  <section class="hero-section hero-wrapper">
    <div class="container position-relative home-section">
      <div class="row">
        <div class="col-12">
          <h1 class="fw-bold main-heading text-dark text-lg-center text-start">
            Create, inspect, and apply <span class="divider"></span> synthetic
            surveillance broadly.
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
          <p class="text-light-dark text-center mobile-text">
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
  </section>
</template>

<style scoped>
.hero-section {
  min-height: calc(100vh - 130px);
  padding-top: 20px;
  /* display: flex;
  justify-content: center;
  align-items: center; */
  position: relative;
}

.hero-wrapper {
  position: relative;
  width: 100%;
}

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
  position: relative;
  text-align: center;
}

.hero-img {
  top: 75px;
  right: 0;
  z-index: -1;
  width: 100%;
  height: auto;
}

.main-heading {
  font-size: 50px;
  line-height: 1.2;
  font-weight: bold;
  /* margin-top: 50px; */
}

.mobile-text {
  margin-top: 15px;
}

@media (max-width: 1199px) {
  .hero-section {
    min-height: max-content;
  }
  .main-heading {
    font-size: 40px;
  }
}

@media (max-width: 991px) {
  .main-heading {
    font-size: 35px;
  }
  .hero-img {
    top: 150px;
  }
  .hero-section {
    min-height: max-content;
  }
}

@media (max-width: 767px) {
  .hero-section {
    min-height: max-content;
  }
  .hero-img {
    top: 200px;
  }

  .mobile-text {
    margin-top: 205px;
  }

  .main-heading {
    font-size: 30px;
    /* margin-top: 75px; */
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

@media (max-width: 576px) {
  .hero-img {
    top: 47%;
  }

  .main-heading {
    font-size: 28px;
    line-height: 1.3;
  }

  .home-section {
    padding-left: 15px;
    padding-right: 15px;
  }
}
</style>
