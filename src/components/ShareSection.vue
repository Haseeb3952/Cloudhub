<template>
  <div>
    <div class="container">
      <div class="row align-items-center py-5 flex-column flex-lg-row">
        <div class="col-12 col-lg-6 order-1 order-lg-0">
          <h6>
            <span class="badge fw-fw-light rounded-pill bg-orange">Share</span>
          </h6>
          <h1 class="fw-bold">
            Share anything you’re <span class="divider"></span>
            working on.
          </h1>
          <p class="my-4">
            Campsite has been instrumental in keeping designers aware of each
            others' work-in-progress in a way that was previously slowing us
            down. It's also one of the only channels where.
          </p>
          <div class="d-flex align-items-center gap-5">
            <div class="d-flex align-items-center gap-2">
              <div
                class="checkmark d-flex justify-content-center align-items-center rounded-circle"
              >
                <img
                  src="../assets/checkmark.svg"
                  class="img-fluid"
                  alt="checkmark"
                />
              </div>
              <div>
                <p class="m-0">Coded</p>
              </div>
            </div>
            <div class="d-flex align-items-center gap-2">
              <div
                class="checkmark d-flex justify-content-center align-items-center rounded-circle"
              >
                <img
                  src="../assets/checkmark.svg"
                  class="img-fluid"
                  alt="checkmark"
                />
              </div>
              <div>
                <p class="m-0">100% Secure</p>
              </div>
            </div>
          </div>
          <div class="d-flex align-items-center gap-2 mt-4">
            <div
              class="bg-play-icon d-flex justify-content-center align-items-center rounded-circle"
            >
              <img
                src="../assets/play-icon.svg"
                class="img-fluid"
                alt="play-icon"
              />
            </div>
            <div><p class="fw-bold m-0">See how it works</p></div>
          </div>
        </div>

        <div class="col-12 col-lg-6 order-0 order-lg-1 mb-4 mb-lg-0">
          <img
            src="../assets/code-frame.png"
            class="img-fluid"
            alt="Code Frame"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.checkmark {
  height: 20px;
  width: 20px;
  background-color: #f6f6f6;
}
.bg-orange {
  background-color: #ff591e;
}
.bg-orange:hover {
  background-color: #fb432c;
}
.bg-play-icon {
  height: 25px;
  width: 25px;
  background-color: #ff591e;
}
@media (max-width: 767px) {
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
