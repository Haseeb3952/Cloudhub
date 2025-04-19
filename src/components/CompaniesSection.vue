<template>
  <div>
    <section class="companies-logo">
      <div class="container justify-content-center align-items-center">
        <div class="row align-items-center gy-3 mt-5">
          <div class="col-6 col-lg-2" v-for="n in 6" :key="n">
            <a :href="'#logo' + n">
              <img
                :src="require(`../assets/company-logo-${n}.svg`)"
                class="img-fluid logo-hover"
                :alt="'company-logo-' + n"
              />
            </a>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.companies-logo {
  margin-top: 350px;
}
@media (max-width: 767px) {
  .companies-logo {
    margin-top: 200px;
  }
}

.logo-hover {
  transition: transform 0.4s ease;
}

.logo-hover:hover {
  transform: scale(1.15);
}
</style>
