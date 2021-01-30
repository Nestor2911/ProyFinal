<template>
  <div class="contact-form-wrapper">
    <figure class="container-comunity__img">
      <img class="iphone" src="@/assets/images/phone.png" alt="fono" />
    </figure>
    <div class="contact-form-phone">
      <div class="contact-form-container-phone">
        <div class="form-title">
          Postula y obtén un 10% de descuento en el programa
        </div>
        <div class="contact-form-GridPhone">
          <div style="position: relative">
            <label for="name" class="input-label"></label>
            <input
              type="text"
              class="input-class"
              name="name"
              placeholder="NOMBRE"
            />
          </div>
          <div style="position: relative">
            <label for="phone" class="input-label"></label>
            <input
              type=""
              name="phone"
              pattern="[0-9]*{9}"
              placeholder="CELULAR"
              class="input-class"
              value
            />
          </div>
          <div style="position: relative">
            <label for="email" class="input-label"></label>
            <input
              type="email"
              name="email"
              class="input-class"
              placeholder="CORREO ELECTRÓNICO"
            />
          </div>
          <div class="form_select">
            <select id="cursos" name="cursos" class="input-select">
              <option value="" selected>PROGRAMAS</option>
              <option>Desarrollo Front-End</option>
              <option>Desarrollo Back-End</option>
              <option>Desarrollo de Aplicativos Móviles</option>
              <option>Diseño de Experiencia del Usuario</option>
              <option>Desarrollo de Videojuegos</option>
            </select>
          </div>
          <label class="check-label" for="check">
            <input class="check-input" type="checkbox" value="false" />
            Acepto las
            <span style="margin-left: 3px; cursor: pointer"
              >Políticas de Privacidad</span
            >
          </label>
          <div class="button-submit-form">Quiero Postular</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PhoneProduct",
};
</script>

<style lang="scss">
@import "@/assets/styles/mery/_phoneProduct.scss";
.input-select {
  height: 50px;
  width: 100%;
  padding: 16px 14px;
  border: 1px solid rgb(139, 144, 153);
  border-radius: 6px;
  padding: 16px 8px;
  outline: none;
  font-size: 12px;
  background: none;
  font-family: Roboto, sans-serif;
  color: rgb(0, 0, 0);
}
</style>
