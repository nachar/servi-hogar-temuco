<template>
  <div id="app">
    <div class="hero-container position-relative">
      <img alt="Ingedoor Temuco background"
           class="hero-container__img w-100 h-100"
           src="./assets/white-gate.jpeg">
      <div class="hero-container__content position-absolute w-100 h-100
      d-flex align-items-center justify-content-center px-4">
        <div class="hero-network">
          <h1 class="m-0 sr-only">Ingedoor Temuco</h1>
          <img class="hero-container__content__logo w-100"
               src="./assets/gate-logo.png"
               alt=">Ingedoor Temuco">
          <div class="mt-4">
            <a class="mx-2" href="mailto:contacto@ingedoor.cl">
              <span class="material-icons-outlined">email</span>
            </a>
            <a class="mx-2" href="https://wa.me/56994034674">
              <span class="material-icons-outlined">whatsapp</span>
            </a>
            <a class="mx-2" href="tel:56994034674">
              <span class="material-icons-outlined">call</span>
            </a>
          </div>
        </div>
      </div>
    </div>

    <div class="services py-5">
      <h2 class="mb-4">Servicios</h2>
      <div class="container">
        <ul class="row list-unstyled d-flex justify-content-center">
          <li class="services-list col-12 col-lg-4">
            <div class="services-list__img">
              <img alt="Vue logo" class="w-100 h-100" src="./assets/electric-gate.jpeg">
            </div>
            <p class="font-weight-bold mt-3">Instalación de portones eléctricos</p>
          </li>
          <li class="services-list col-12 col-lg-4">
            <div class="services-list__img">
              <img alt="Vue logo" class="w-100 h-100" src="./assets/gate.jpeg">
            </div>
            <p class="font-weight-bold mt-3">Venta de motores para portones</p>
          </li>
        </ul>
      </div>
    </div>

    <div class="contact py-5">
      <div class="container">
        <div class="row">
          <div class="col">
            <h2 class="mb-4">Contacto</h2>
            <p>
              La mejor empresa de multiservicios profesionales para el hogar y
              empresarial en la novena región.
            </p>
            <p class="mb-4">
              Trabajo de calidad y con los mejores profesionales del sur de Chile.
            </p>
            <a class="mx-2" href="mailto:contacto@ingedoor.cl">
              <span class="material-icons-outlined">email</span>
            </a>
            <a class="mx-2" href="https://wa.me/56994034674">
              <span class="material-icons-outlined">whatsapp</span>
            </a>
            <a class="mx-2" href="tel:56994034674">
              <span class="material-icons-outlined">call</span>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style lang="scss">
@import "src/scss/custom";
</style>
