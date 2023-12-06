<template>
  <div class="bg d-flex flex-column ">
    <div class="cards d-flex ">
      <div class=" d-flex justify-space-around flex-column">
        <div class="hidden-sm-and-down">
        <p class="text-white d-flex align-self-start text-h2">О Компании</p>
        </div>
        <div class="hidden-md-and-up hidden">
        <p class="text-white d-flex align-self-start text-h5">О Компании</p>
        </div>
        <div>
          <p class="text-h6">«Для нас лифт – это уникальный механизм, а не просто квадратный короб, который перемещает Вас вверх-вниз. Поездка в нашем лифте – это абсолютно неповторимый опыт для любого пассажира. В основе создания лифта лежат технологии высочайшего уровня, благодаря чему меняется восприятие лифтав целом».</p>
        <p class="text-h6">Мы компания Shamollift, предоставляющая нашим клиентам самое передовое лифтовое оборудование и полный спектр услуг от проектирования до технического обслуживания пассажирских, кухонных, строительных, автомобильных и грузовых лифтов, а также эскалаторов.</p>
        </div>
      </div>
      <img src="../assets/img/about_us_1.png" alt="">
    </div>

    <div class="cards card-2 d-flex ">
      <p class="cards-text text-h6">Компания была создана в 2008 году в Турции, с тех пор компания с каждым годом все совершенствует свою продукцию занимая достойное место на мировом рынке лифтового оборудования. Компания занимается производством лифтов, пассажирского, грузового типа, основанных на гидравлике и электрике. Благодаря накопленному опыту, лифты Shamollift отличаются надежностью, легкостью установки и удобством обслуживания. На территорию Узбекистана продукция бренда поступает уже полностью укомплектованной и готовой к установке. На территорию Узбекистана продукция бренда поступает уже полностью укомплектованной и готовой к установке.</p>
      <img src="../assets/img/about_us_2.png" alt="">
    </div>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
.cards-text{
  margin-left: 25px;
}
  .cards{
    margin: 50px;
  }
.card-2{
  flex-direction: row-reverse;
}
  .bg{
    padding: 64px;
    background-color: #111;
    color: #afafaf;
  }


@media screen and (max-width: 1200px) {
  .bg{
    padding: 20px;
  }

  .cards{
    margin: 10px 0;
    flex-direction: column;
  }

  .cards-text{
    margin: 0;
  }
}
</style>