<script>
  export default {
    mounted () {
      window.scrollTo(0, 0)
    }
  }
</script>

<template>
  <div class="container d-flex flex-column">
    <div class="big-lifts mt-5 d-flex align-start flex-column">
      <p class="text-h4 mb-4">Грузовые лифты</p>
      <div class="d-flex align-center flex-wrap">
        <img class="about-img" src="../assets/img/product_1.png">
        <p class="about-text pa-2 text-h5 text-grey"> <span class="text-white">Shamollift</span> оказывает полный комплекс услуг по поставке, монтажу и обслуживанию пассажирских лифтов. Наши специалисты имеют большой опыт работы с импортными и отечественными подъемниками любого типа и года выпуска. У нас Вы можете удобно и безопасно приобрести лифты пассажирские для. Все электрические пассажирские лифты в продаже отвечают требованиям стандартов Республики Узбекистан. Мы предлагаем только сертифицированное оборудование. </p>
      </div>
    </div>

    <div class="advantages-of-our-lifts mt-16 d-flex align-start flex-column">
      <div class="hidden-sm-and-down"><p class="pa-2 text-h4 mb-4 mt-10">Почему стоит купить пассажирский лифт в компании Shamollift</p></div>
      <div class="hidden-md-and-up"><p class="pa-1 text-h5 mb-2 mt-10">Почему стоит купить пассажирский лифт в компании Shamollift</p></div>
      <div class="crads d-flex align-center justify-center flex-wrap">
        <v-card class="card d-flex align-start flex-column">
          <img height="50" src="../assets/img/scale.svg" alt="">
          <p class="mt-2 text-subtitle-2">
            Лифты, рассчитанные на эксплуатацию в жилых зданиях для подъема людей, грузоподъемностью от 240 килограмм до 1000 килограмм, и помимо жилых зданий (гостиницы, больницы, торговые центры) для подъема людей и грузов от 630 килограмм до 1600 килограмм.
          </p>
        </v-card>

        <v-card class="card d-flex align-start flex-column">
          <img height="50" src="../assets/img/group_add.svg" alt="">
          <p class="mt-2 text-subtitle-2">
            Номинальная скорость лифтов, рассчитанных на подъем людей, грузоподъемностью от 3 до 21 человек, варьируется от 0,40 м/сек до 2,5 м/сек, в зависимости от высоты здания.
          </p>
        </v-card>

        <v-card class="card d-flex align-start flex-column">
          <img height="50" src="../assets/img/shield-tick.svg" alt="">
          <p class="mt-2 text-subtitle-2">
            Номинальная скорость лифтов, рассчитанных на подъем людей, грузоподъемностью от 3 до 21 человек, варьируется от 0,40 м/сек до 2,5 м/сек, в зависимости от высоты здания.
          </p>
        </v-card>

        <v-card class="card d-flex align-start flex-column">
          <img height="50" src="../assets/img/readiness_score.svg" alt="">
          <p class="mt-2 text-subtitle-2">
            Лифты для подъема людей строятся в процессе расчетов движения, а предварительные проекты выполняются в зависимости от расчетов и проектов, и монтируются на местах.
          </p>
        </v-card>
      </div>
    </div>

    <img class="lift-img" src="../assets/img/about_lift.png" alt="">
  </div>
</template>

<style scoped>
.card{
  padding: 20px;
  margin: 20px;
  background-color: #111;
  border: 1px solid #3e3e3e;
  color: white;
  border-radius: 10px;
  width: 290px;
  height: 300px;
}
.container{
  padding: 20px 60px;
}
.about-img{
  width: 500px;
  padding-right: 50px;
}
.about-text{
  width: 40%;
}
.lift-img{
  width: 100%;
}
@media screen and (max-width: 960px) {
  .container{
    padding: 10px;
  }
  .about-img{
    width: 100%;
    padding: 0;
    margin: 0;
    margin-top: 20px;
  }
  .about-text{
    width: 100%;
  }

  .card{
    width: 250px;
    padding: 5px;
    margin: 10px 3px;
  }
}
</style>
