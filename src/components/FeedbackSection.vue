<template>
  <div>
    <div class="container">
      <div class="row align-items-center py-5 flex-column flex-lg-row">
        <!-- Image -->
        <div class="col-12 col-lg-6 mb-4 mb-lg-0">
          <img
            src="../assets/feedback-frame.svg"
            class="img-fluid"
            alt="Code Frame"
          />
        </div>

        <!-- Content -->
        <div class="col-12 col-lg-6 p-lg-5 p-2">
          <h6>
            <span class="badge fw-light rounded-pill bg-orange">Feedback</span>
          </h6>
          <h1 class="fw-bold">
            Better feedback at <span class="divider"></span> the right time.
          </h1>
          <p class="my-4">
            Campsite has been instrumental in keeping designers aware of each
            others' work-in-progress in a way that was previously slowing us
            down. It's also one of the only channels where.
          </p>
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
            <p class="fw-bold m-0">See how it works</p>
          </div>
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
