<template>
  <div class="d-flex flex-column align-center">
    <div class="hidden-sm-and-down"><p class="text-h4 text-white">Подпишитесь на нашу рассылку</p></div>
    <div class="hidden-md-and-up"><p class="text-h6 text-white">Подпишитесь на нашу рассылку</p></div>
    <div class="my-5 d-flex align-center justify-center flex-wrap">
      <v-btn class="link ma-4"> <img class="mr-2" src="../assets/img/Telegram.svg" alt=""> Telegram </v-btn>
      <v-btn class="link ma-4"> <img class="mr-2" src="../assets/img/Instagram.svg" alt=""> Instagram </v-btn>
      <v-btn class="link ma-4"> <img class="mr-2" src="../assets/img/Group.svg" alt=""> YouTube </v-btn>
      <v-btn class="link ma-4"> <img class="mr-2" src="../assets/img/Facebook.svg" alt=""> Facebook </v-btn>
    </div>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
  .link{
    background: linear-gradient(140deg, #5C5C5C 1.86%, #CDCBCB 44.24%, #5C5C5C 96.52%);
  }
</style>