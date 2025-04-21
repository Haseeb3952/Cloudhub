<template>
  <div>
    <section class="companies-logo">
      <div class="container">
        <div class="row justify-content-center align-items-center gy-4">
          <div class="col-6 col-sm-4 col-md-3 col-lg-2">
            <a
              href="#logo1"
              class="d-flex justify-content-center align-items-center"
            >
              <img
                src="../assets/company-logo-1.svg"
                alt="company-logo-1"
                class="img-fluid logo-hover mobile-hidden"
              />
            </a>
          </div>
          <div class="col-6 col-sm-4 col-md-3 col-lg-2">
            <a
              href="#logo2"
              class="d-flex justify-content-center align-items-center"
            >
              <img
                src="../assets/company-logo-2.svg"
                alt="company-logo-2"
                class="img-fluid logo-hover mobile-hidden"
              />
            </a>
          </div>
          <div class="col-6 col-sm-4 col-md-3 col-lg-2">
            <a
              href="#logo3"
              class="d-flex justify-content-center align-items-center"
            >
              <img
                src="../assets/company-logo-3.svg"
                alt="company-logo-3"
                class="img-fluid logo-hover"
              />
            </a>
          </div>
          <div class="col-6 col-sm-4 col-md-3 col-lg-2">
            <a
              href="#logo4"
              class="d-flex justify-content-center align-items-center"
            >
              <img
                src="../assets/company-logo-4.svg"
                alt="company-logo-4"
                class="img-fluid logo-hover"
              />
            </a>
          </div>
          <div class="col-6 col-sm-4 col-md-3 col-lg-2 order-lg-0 order-1">
            <a
              href="#logo5"
              class="d-flex justify-content-center align-items-center"
            >
              <img
                src="../assets/company-logo-5.svg"
                alt="company-logo-5"
                class="img-fluid logo-hover"
              />
            </a>
          </div>
          <div class="col-6 col-sm-4 col-md-3 col-lg-2 order-lg-1 order-0">
            <a
              href="#logo6"
              class="d-flex justify-content-center align-items-center"
            >
              <img
                src="../assets/company-logo-6.svg"
                alt="company-logo-6"
                class="img-fluid logo-hover"
              />
            </a>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style>
.companies-logo {
  margin-top: 250px;
}

@media (max-width: 767px) {
  .companies-logo {
    margin-top: 125px;
  }

  .mobile-hidden {
    display: none;
  }
}

.logo-hover {
  transition: transform 0.3s ease;
}

.logo-hover:hover {
  transform: scale(1.15);
}
</style>
