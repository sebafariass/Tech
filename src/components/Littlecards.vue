<template>
  <section class="container color_font">
    <div id="prueba" class="row">
      <div class="card container col-sm-12 col-md-3 col-xl-3">
        <div class="card-body">
          <div class="bigCards__contenido">
            <div class="contenedor">
              <img
                class="text_linear"
                src="../assets/guion.png"
                alt="Subrayado_Down"
              />
              <div class="texto-encima"><p>AVANCE FINANCIERO</p></div>
            </div>

            <h2>
              <span> <i id="usd" class="far fa-usd-circle"></i></span>
              60 %
            </h2>
            <p>
              Real: MUSD $6
              <br />
              Total: MUSD $10
            </p>
          </div>
        </div>
      </div>
      <div class="card container col-sm-12 col-md-3 col-xl-3">
        <div class="card-body">
          <div class="bigCards__contenido">
            <div class="contenedor">
              <img
                class="text_linear_dos"
                src="../assets/guion.png"
                alt="Subrayado_Down"
              />
              <div class="texto-encima"><p>ACELERACIÓN</p></div>
            </div>

            <h2>
              <span> <i class="fad fa-chart-line"></i></span>
              60 %
            </h2>
            <p>
              Real: MUSD $6
              <br />
              Total: MUSD $10
            </p>
          </div>
        </div>
      </div>
      <div class="card container col-sm-12 col-md-4 col-xl-3">
        <div class="card-body">
          <div class="bigCards__contenido">
            <div class="contenedor">
              <img
                class="text_linear_tres"
                src="../assets/guion.png"
                alt="Subrayado_Down"
              />
              <div class="texto-encima"><p>ESTIMADO CIERRE</p></div>
            </div>

            <h6>Mes Estimado de Cierre:</h6>
            <h5><strong>OCTUBRE 2021</strong></h5>
            <h6 >Acelaración Estimada:</h6>

            <h5>
              <strong>2 MESES</strong>
            </h5>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Littlecards",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#prueba {
  display: flex;
  justify-content: space-between;
  text-align: center;
}

.card {
  display: flex;
  width: 420px;
  height: 210px;
}
.bigCards {
  margin: 1px solid black;
  fill: black;
}
.bigCards__contenido {
  color: #5a5a5a;
  font-family: "Roboto", sans-serif;
  width: auto;
  font-weight: bolder;
}

.card-body {
  display: flex;
  justify-content: space-around;
  text-align: center;
  padding-top: 30px;
  height: auto;
}

.contenedor {
  position: relative;
  display: inline-block;
  text-align: center;
}
.texto-encima {
  position: relative;
  bottom: 40px;
  font-weight: bold;
  color: #5a5a5a;
  font-family: "Roboto", sans-serif;
}

.text_linear {
  position: relative;
  right: 62px;
}
.text_linear_dos {
  position: relative;
  right: 35px;
}
.text_linear_tres {
  position: relative;
  right: 50px;
}

p {
  margin-bottom: 5px;
}

.color_font {
  color: #5a5a5a;
  font-family: "Roboto", sans-serif;
}

[class*="col-"] {
  width: 100%;
}

@media only screen and (min-width: 600px) {
  /* For tablets: */
  .col-s-1 {
    width: 8.33%;
  }
  .col-s-2 {
    width: 16.66%;
  }
  .col-s-3 {
    width: 25%;
  }
  .col-s-4 {
    width: 33.33%;
  }
  .col-s-5 {
    width: 41.66%;
  }
  .col-s-6 {
    width: 50%;
  }
  .col-s-7 {
    width: 58.33%;
  }
  .col-s-8 {
    width: 66.66%;
  }
  .col-s-9 {
    width: 75%;
  }
  .col-s-10 {
    width: 83.33%;
  }
  .col-s-11 {
    width: 91.66%;
  }
  .col-s-12 {
    width: 100%;
  }
}
@media only screen and (min-width: 768px) {
  /* For desktop: */
  .col-1 {
    width: 8.33%;
  }
  .col-2 {
    width: 16.66%;
  }
  .col-3 {
    width: 25%;
  }
  .col-4 {
    width: 33.33%;
  }
  .col-5 {
    width: 41.66%;
  }
  .col-6 {
    width: 50%;
  }
  .col-7 {
    width: 58.33%;
  }
  .col-8 {
    width: 66.66%;
  }
  .col-9 {
    width: 75%;
  }
  .col-10 {
    width: 83.33%;
  }
  .col-11 {
    width: 91.66%;
  }
  .col-12 {
    width: 100%;
  }
}

@media (max-width: 800px) {
  .card {
    margin-top: 20px;
  }
}
</style>
