<template>
  <section class="container cardbar_font">
    <div class="card-group" id="Cardbar_fondo">
      <div class="card">
        <div class="card-body pt-5 principal">
          <h5 class="card-text text-center">MUSD $10</h5>
        </div>
      </div>

      <div class="card">
        <div class="card-body pt-3">
          <h5 class="card-title texto_principal ">PLAZO</h5>
          <h4 class="card-text_extendido">36 MESES</h4>
          <strong><h6>ENE 2019-DIC 2021</h6></strong>
        </div>
      </div>

      <div class="card">
        <div class="card-body pt-3">
          <h5 class="card-title">MONTO GASTADO</h5>
          <p class="card-text">MUSD$ 6</p>
        </div>
      </div>

      <div class="card">
        <div class="card-body">
          <h5 class="card-title pt-3">AVANCE TEMPORAL</h5>
          <p class="card-text">18 Meses</p>
        </div>
      </div>

      <div class="card">
        <div class="card-body">
          <h5 class="card-title pt-3">CANTIDAD EDPS</h5>
          <p class="card-text">18</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Cardbar",
};
</script>

<style>
.cardbar_font {
  color: #5a5a5a;
  font-family: "Roboto", sans-serif;
}

.card-body {
  padding: 0;
  margin: 0;
  font-weight: 700;
  color: #5a5a5a;
  font-family: "Roboto", sans-serif;
}

h6 {
  font-weight: 700;
}
h5 {
  font-weight: 700;
}
.card-title {
  font-weight: 700;
}
.texto_principal{
  margin: 0;
}
.card {
  display: flex;
}

.card-text_extendido {
  margin: 0;
  padding: 0;
  font-weight: bold;
}

@media (max-width: 720px) {
  .principal {
    padding-bottom: 30px;
  }
}
</style>