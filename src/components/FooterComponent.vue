<template>
  <footer class="contact py-5">
    <div class="container">
      <div class="row">
        <div class="col">
          <h2 class="mb-4">
            Contacto
          </h2>
          <p>
            La mejor empresa de multiservicios profesionales para el hogar y
            para empresas en la novena región.
          </p>
          <p class="mb-4">
            Trabajo de calidad y con los mejores profesionales del sur de Chile.
          </p>
          <a
            class="mx-2"
            href="mailto:contacto@ingedoor.cl"
            title="Correo electrónico">
            <span class="material-icons-outlined">email</span>
          </a>
          <a
            class="mx-2"
            href="https://wa.me/56994034674"
            title="Whatsapp">
            <span class="material-icons-outlined">whatsapp</span>
          </a>
          <a
            class="mx-2"
            href="tel:56994034674"
            title="Teléfono">
            <span class="material-icons-outlined">call</span>
          </a>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterComponent',
};
</script>

<style scoped lang="scss">
.contact {
  background-color: #35322a;

  p,
  h2 {
    color: #fff;
  }
  a {
    color: #fff;
    &:hover,
    &:active,
    &:focus,
    &:visited {
      color: #fff;
    }

    span {
      font-size: 2.5rem;
    }
  }
}
</style>
