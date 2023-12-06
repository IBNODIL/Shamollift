<template>
  <div class="contact text-white mt-10 d-flex align-center justify-space-around">
    <div class="forms d-flex flex-column justify-space-between">
      <div class="mb-10 hidden-sm-and-down"><p class="text-h4 text-white">Связаться с нами</p></div>
      <div class="mb-5 hidden-md-and-up"><p class="text-h6 text-white">Связаться с нами</p></div>
      <v-text-field label="Номер телефона" variant="solo" color="black" prefix="+998"></v-text-field>
      <v-textarea label="Сообщение" auto-grow variant="solo"></v-textarea>
      <v-btn class="my-3 v-btn--size-small linear-gradient-btn text-black">Оставить заявку<v-icon class="mx-1">mdi-arrow-right</v-icon></v-btn>
      <p class="d-flex my-2 align-center text-body-1"><img height="25" src="../assets/img/call.svg" class="mr-2" alt=""> +998 91 214 34 72</p>
      <p class="d-flex my-2 align-center text-body-1"><img height="25" src="../assets/img/mail.svg" class="mr-2" alt=""> Shamollift@gmail.com</p>
      <p class="d-flex my-2 align-center text-body-1"><img height="25" src="../assets/img/location_on.svg" class="mr-2" alt=""> Toshkent shahar Yashnabod tumani Olmos mahallasi Yakkatol 3-tor ko’chasi 38/3 uy</p>
    </div>

    <div class="map">
      <iframe src="https://www.google.com/maps/embed?pb=!1m13!1m8!1m3!1d5996.9787180366175!2d69.365!3d41.276453!3m2!1i1024!2i768!4f13.1!3m2!1m1!2zNDHCsDE2JzM1LjIiTiA2OcKwMjEnNTQuMCJF!5e0!3m2!1suz!2s!4v1701886347552!5m2!1suz!2s" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
iframe{
  height: 500px;
  width: 100%;
  border-radius: 20px;
}
.contact{
  padding: 10px 50px;
}
.map{
  padding: 10px;
  width: 50%;
}
.forms{
  padding: 10px 20px;
  width: 50%;
}
.linear-gradient-btn{
  width: 250px;
  background: linear-gradient(140deg, #5C5C5C 1.86%, #CDCBCB 44.24%, #5C5C5C 96.52%);
}

@media screen and (max-width: 960px) {
  .contact{
    padding: 10px !important;
    flex-direction: column;
  }

  .forms, .map{
    width: 100%;
  }
}
</style>