<template>
  <div class="d-flex flex-column align-center">
    <p class="text-h4 text-white mb-5">Наша продукция</p>

    <div class="d-flex flex-wrap align-center">
      <v-card class="card ma-4 pa-4 d-flex flex-column">
        <img src="../assets/img/product_1.png" alt="">
        <div class="hidden-sm-and-down"><p class="text-h5 mx-0 px-0 mt-2"> <b>Грузовые лифты</b> </p></div>
        <div class="hidden-md-and-up"><p class="text-body-1 mx-0 px-0 mt-2"> <b>Грузовые лифты</b> </p></div>
        <v-btn class="linear-gradient-btn text-none text-black text-subtitle-1 my-2" to="/about-lift" block><b>Подробное</b></v-btn>
      </v-card>

      <v-card class="card ma-4 pa-4 d-flex flex-column">
        <img src="../assets/img/product_2.png" alt="">
        <div class="hidden-sm-and-down"><p class="text-h5 mx-0 px-0 mt-2"> <b>Больничные лифты</b> </p></div>
        <div class="hidden-md-and-up"><p class="text-body-1 mx-0 px-0 mt-2"> <b>Больничные лифты</b> </p></div>
        <v-btn class="linear-gradient-btn text-none text-black text-subtitle-1 my-2" to="/about-lift" block><b>Подробное</b></v-btn>
      </v-card>

      <v-card class="card ma-4 pa-4 d-flex flex-column">
        <img src="../assets/img/product_4.png" alt="">
        <div class="hidden-sm-and-down"><p class="text-h5 mx-0 px-0 mt-2"> Лифты <b>для инвалидов</b> </p></div>
        <div class="hidden-md-and-up"><p class="text-body-1 mx-0 px-0 mt-2"> Лифты <b>для инвалидов</b> </p></div>
        <v-btn class="linear-gradient-btn text-none text-black text-subtitle-1 my-2" to="/about-lift" block><b>Подробное</b></v-btn>
      </v-card>

      <v-card class="card ma-4 pa-4 d-flex flex-column">
        <img src="../assets/img/product_5.png" alt="">
        <div class="hidden-sm-and-down"><p class="text-h5 mx-0 px-0 mt-2"> <b>Кухонные лифты</b> </p></div>
        <div class="hidden-md-and-up"><p class="text-body-1 mx-0 px-0 mt-2"> <b>Кухонные лифты</b> </p></div>
        <v-btn class="linear-gradient-btn text-none text-black text-subtitle-1 my-2" to="/about-lift" block><b>Подробное</b></v-btn>
      </v-card>

      <v-card class="card ma-4 pa-4 d-flex flex-column">
        <img src="../assets/img/product_5.png" alt="">
        <div class="hidden-sm-and-down"><p class="text-h5 mx-0 px-0 mt-2"> <b>Коттеджные лифты</b> </p></div>
        <div class="hidden-md-and-up"><p class="text-body-1 mx-0 px-0 mt-2"> <b>Коттеджные лифты</b> </p></div>
        <v-btn class="linear-gradient-btn text-none text-black text-subtitle-1 my-2" to="/about-lift" block><b>Подробное</b></v-btn>
      </v-card>
    </div>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
.linear-gradient-btn{
  background: linear-gradient(140deg, #5C5C5C 1.86%, #CDCBCB 44.24%, #5C5C5C 96.52%);
  color: black;
}

.card{
  border-radius: 15px;
  background-color: #111;
  color: white;
  border: 1px solid grey;
}

@media screen and (max-width: 960px) {
  .card{
    padding: 10px !important;
    margin: 20px 10px !important;
  }
}

@media screen and (max-width: 450px) {
  .card{
    width: 80%;
  }

  .card img{
    width: 100%;
  }
}
</style>