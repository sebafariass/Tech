<template>
  <section class="container">
    <div class="row total_card">
      <div class="graph_card col-sm-12 col-md-8 col-xl-6">
        <div class="card card_graphic">
            <div class="text_card_principal">
                <div class="sub_text ">
            <h4 class=" text-center font-weight-bold">
             CONSUMO HISTÓRICO 
            </h4>
            <h5 class="text_hight font-weight-bold">Editar Periodo</h5>
            </div>

           <div class="point_img">
                <div  class="point_purple">
                <img src="../assets/circuloPurple.png" alt="Punto_Purple">
                <h5>Presupuesto</h5>
            </div>
                 <div class="point_green">
                <img src="../assets/circuloGreen.png" alt="Punto_Green">
                <h5>Real</h5>
            </div>
           </div>
            </div>
         
                <div class="imgen_card">
                    <img src="../assets/linear_green.png" class="card-img-top imagen1" alt="Barra_Green">
                <div>
                    <img src="../assets/linear_purple.png" class="card-img-top imagen2" alt="Barra_Green">
                </div>
                </div>
         
        </div>
      </div>

      <div class="row table_graph col-md-8 col-sm-12 col-xl-6">
        <div class="card card_graphic col-xl-10">
          <div class="card-body">
            <h5 class="py-3">ANÁLISIS PARTIDA</h5>
            <table class="table table-sm">
              <thead>
                <tr>
                  <th scope="col"></th>
                  <th scope="col" class="mb-4">Partida</th>
                  <th scope="col">
                    Monto <br />
                    USD
                  </th>
                  <th scope="col">% Avance</th>
                </tr>
              </thead>
              <tbody>
                <br />
                <tr>
                  <th>
                    <img
                      id="circule_imagn"
                      src="../assets/circule.png"
                      alt="Circule_Table"
                    />
                  </th>
                  <td>Item 1</td>
                  <td>$80.000</td>
                  <td>20%</td>
                </tr>
                <tr>
                  <th>
                    <img
                      id="circule_imagn"
                      src="../assets/circule.png"
                      alt="Circule_Table"
                    />
                  </th>
                  <td>Item 2</td>
                  <td>$16.000</td>
                  <td>25%</td>
                </tr>
                <tr>
                  <th>
                    <img
                      id="circule_imagn"
                      src="../assets/circule.png"
                      alt="Circule_Table"
                    />
                  </th>
                  <td>Item 3</td>
                  <td>$22.800</td>
                  <td>15%</td>
                </tr>
                <tr>
                  <th>
                    <img
                      id="circule_imagn"
                      src="../assets/circule.png"
                      alt="Circule_Table"
                    />
                  </th>
                  <td>Item 4</td>
                  <td>$14.000</td>
                  <td>30%</td>
                </tr>

                <tr >
                
                   
                  <td >Gasto Generales</td>
                  <td class="especial">$30.000</td>
                  <td class="especial">32%</td>
                </tr>

                 <tr>
                  <td >Utilidades</td>
                  <td class="especial">$20.000</td>
                  <td class="especial">30%</td>
                  <td> </td>
                </tr>
                 <tr>
                  <td >Reajustes</td>
                  <td class="especial">$100.000</td>
                  <td class="especial">30%</td>
                </tr>
                <tr>
                  <td >Otros</td>
                  <td class="especial">$100.000</td>
                  <td class="especial">30%</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
   
    </div>

  </section>
</template>

<script>
export default {
  name: "Cardgraph",
};
</script>

<style lang="scss">
.point_img{
    display:flex;
    justify-content: space-around;
    align-items: flex-start;
}

.text_hight{
    display:flex;
    justify-content: center;
}

.point_purple{
    display: flex;
}
.point_green{
    display: flex;
}


.text_card_principal{
    display:flex;
    align-items: flex-end;
}


.graph_card {
  display: flex;
  justify-content: space-between;
  height: 200px;
  
}

.imagen_card{
    position: absolute;
}
.imagen1{
    z-index:2;
    position: relative;
    top: 90px;
    
     
   
}
.imagen2{
    z-index:31;
    position: relative;
    bottom: 35px;
    
     
   
    
}

.sub_text{
    display: flex;
    align-items: flex-end;
    color: #5a5a5a;
  font-family: "Roboto", sans-serif;
}

h5{
    font-weight: bold;
}



.card_graphic{
    height: 427px;
}

@media (max-width:1200px){
    .card{
        margin-top:20px;
    }
}

@media (max-width:1200px){
    .table_graph{
        margin-top:90px;
    }
}

</style>
