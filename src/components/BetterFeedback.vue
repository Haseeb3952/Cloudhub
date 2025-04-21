<template>
  <div>
    <section class="bg-feedback py-5">
      <div class="container">
        <p class="text-lg-center text-start text-white m-0">Best time here</p>
        <h1 class="text-lg-center text-start text-white mb-lg-5 mb-3">
          Better feedback at the right time.
        </h1>

        <div class="bg-black pb-5 rounded-4">
          <div class="custom-bg-box-color mx-lg-5 mx-0 pt-lg-4 pt-0 rounded-3">
            <div class="row align-items-center p-3 pt-lg-0 pt-5">
              <div class="col-12 col-lg-6 mb-3 mb-lg-0">
                <div class="d-flex justify-content-lg-start gap-3">
                  <div class="bg-cloudbox p-2 rounded-2">
                    <img
                      src="../assets/cloud-box.svg"
                      class="img-fluid"
                      alt="cloud-box"
                    />
                  </div>
                  <div>
                    <h6 class="text-white m-0">Cloudhub</h6>
                    <p class="text-secondary m-0">2m ago in Brand</p>
                  </div>
                </div>
              </div>
              <div class="col-12 col-lg-6 text-lg-end">
                <button class="btn px-4 bg-orange rounded-pill text-white">
                  View Post
                </button>
              </div>
            </div>

            <div class="row align-items-center p-3">
              <div class="col-12 col-lg-6 d-flex align-items-center gap-3">
                <div class="d-flex align-items-center">
                  <img
                    src="../assets/person-1.svg"
                    class="img-fluid"
                    alt="feedback person"
                  />
                  <img
                    src="../assets/person-2.svg"
                    class="img-fluid feedback-person"
                    alt="feedback person"
                  />
                  <img
                    src="../assets/person-3.svg"
                    class="img-fluid feedback-person"
                    alt="feedback person"
                  />
                </div>
                <p class="text-white mb-0 ms-3 mobile-view-hidden">
                  3 people are looking for feedback this week
                </p>
              </div>
              <div class="col-12 col-lg-6 text-center text-lg-end mt-3 mt-lg-0">
                <div class="d-flex align-items-center justify-content-between">
                  <p class="text-white text-start mb-0 desktop-view-hidden">
                    3 people are looking for feedback this week
                  </p>
                  <img
                    src="../assets/left-arrow.svg"
                    class="img-fluid"
                    alt="left-arrow"
                    style="max-height: 30px"
                  />
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="row my-1 gy-3">
          <div class="col-12 col-lg-4">
            <div class="box rounded-4 bg-dark p-4 h-100">
              <img
                src="../assets/mentions.svg"
                class="img-fluid"
                alt="mentions"
              />
              <h6 class="text-white mt-2">Mentions</h6>
              <p class="box-text m-0">
                Mention anyone on your team to include them in a post.
              </p>
            </div>
          </div>

          <div class="col-12 col-lg-4">
            <div class="box rounded-4 bg-dark p-4 h-100">
              <img src="../assets/polls.svg" class="img-fluid" alt="polls" />
              <h6 class="text-white mt-2">Polls</h6>
              <p class="box-text m-0">
                Get a quick gut check from the team on design options.
              </p>
            </div>
          </div>

          <div class="col-12 col-lg-4">
            <div class="box rounded-4 bg-dark p-4 h-100">
              <img
                src="../assets/resolve.svg"
                class="img-fluid"
                alt="resolve"
              />
              <h6 class="text-white mt-2">Resolve comments</h6>
              <p class="box-text m-0">
                Mark comments as resolved to keep the conversation focused.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.bg-feedback {
  background: linear-gradient(rgba(251, 67, 44, 1), rgba(255, 89, 30, 1));
}
.bg-orange {
  background-color: #ff591e;
}
.bg-orange:hover {
  background-color: #fb432c;
}
.bg-cloudbox {
  background-color: #363636;
}
.box-text {
  color: #737373;
}
.feedback-person {
  margin-left: -15px;
}
.custom-bg-box-color {
  background-color: #222222;
}

.bg-black {
  background-color: #000000;
  padding-bottom: 20px;
}

.mobile-view-hidden {
  display: block;
}

.desktop-view-hidden {
  display: none;
}

@media (max-width: 767.98px) {
  .mobile-view-hidden {
    display: none;
  }
  .desktop-view-hidden {
    display: block;
    font-size: 13px;
  }
}
</style>
