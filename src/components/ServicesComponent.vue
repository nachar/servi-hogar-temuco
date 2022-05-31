<template>
  <section class="services py-5">
    <h2 class="mb-4">Servicios</h2>
    <div class="container">
      <ul class="row list-unstyled d-flex justify-content-center">
        <li class="services-list col-12 col-lg-4">
          <div class="services-list__img">
            <img alt="Vue logo" class="w-100 h-100" src="../assets/electric-gate.jpeg">
          </div>
          <p class="font-weight-bold mt-3">Instalación de portones eléctricos</p>
        </li>
        <li class="services-list col-12 col-lg-4">
          <div class="services-list__img">
            <img alt="Vue logo" class="w-100 h-100" src="../assets/gate.jpeg">
          </div>
          <p class="font-weight-bold mt-3">Venta de motores para portones</p>
        </li>
      </ul>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ServicesComponent',
};
</script>

<style scoped lang="scss">
.services-list {
  &__img {
    height: 200px;
    img {
      object-fit: cover;
    }
  }
}
</style>
