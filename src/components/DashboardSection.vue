<template>
  <div>
    <section class="bg-dashboard pt-5">
      <div class="container">
        <h1 class="text-white text-center fw-bold pt-4">
          Keep every one in the loop
        </h1>
        <p class="text-white text-center">
          All good things start with a homepage. Get
          <span class="divider"></span> inspired without breaking your wallet.
        </p>
        <div class="d-flex justify-content-center align-items-center">
          <button class="btn bg-white rounded-pill fw-bold px-4">
            Start for free
          </button>
        </div>
        <div class="d-flex justify-content-center align-items-center">
          <img
            src="../assets/dashboard-frame.svg"
            class="img-fluid mt-5"
            alt="dashboard frame"
          />
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.bg-dashboard {
  background: linear-gradient(rgba(251, 67, 44, 1), rgba(255, 89, 30, 1));
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
