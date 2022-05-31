<template>
  <section class="hero-container position-relative">
    <img alt="Ingedoor Temuco background"
         class="hero-container__img w-100 h-100"
         src="../assets/white-gate.jpeg">
    <div class="hero-container__content position-absolute w-100 h-100
    d-flex align-items-center justify-content-center px-4">
      <div>
        <h1 class="m-0 sr-only">Ingedoor Temuco</h1>
        <img class="hero-container__content__logo w-100"
             src="../assets/gate-logo.png"
             alt=">Ingedoor Temuco">
        <div class="hero-network mt-4">
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
  </section>
</template>

<script>
export default {
  name: 'HeroComponent',
};
</script>

<style scoped lang="scss">
.hero-container {
  height: 100vh;
  overflow: hidden;
  &__img {
    object-fit: cover;
  }
  &__content {
    top: 0;
    left: 0;
    background-color: rgba(255, 255, 255, .8);

    h1 {
      color: #fff;
      font-size: 5rem;
      font-weight: 900;
    }

    &__logo {
      max-width: 500px;
    }
  }
}

.hero-network {
  a {
    color: #35322a;
    &:hover,
    &:active,
    &:focus,
    &:visited {
      color: #35322a;
    }

    span {
      font-size: 2.5rem;
    }
  }
}
</style>
