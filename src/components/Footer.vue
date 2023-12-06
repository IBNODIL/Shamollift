<template>
  <div class="footer d-flex align-center flex-column">
    <div class="links-and-img d-flex align-center justify-space-between flex-wrap">
      <img height="40" src="../assets/img/logo.png" alt="">
      <div>
        <v-list class="grey d-flex">
          <v-list-item>
            <v-btn class="grey"><a href="/#about-company">О Компании</a></v-btn>
          </v-list-item>

          <v-list-item>
            <v-btn class="grey"><a href="/#products">Продукция</a></v-btn>
          </v-list-item>

          <v-list-item>
            <v-btn class="grey"><a href="/#advantages">Услуги</a></v-btn>
          </v-list-item>
        </v-list>
      </div>
    </div>
    <hr>
    <div class="links-and-img d-flex align-center justify-space-between flex-wrap">
      <div class="images d-flex align-center">
        <img class="ma-2" height="20px" src="../assets/img/Telegram (1).svg" alt="">
        <img class="ma-2" height="20px" src="../assets/img/Instagram (1).svg" alt="">
        <img class="ma-2" height="20px" src="../assets/img/Group (1).svg" alt="">
        <img class="ma-2" height="20px" src="../assets/img/Facebook (1).svg" alt="">
      </div>

      <p class="text-subtitle-2 text-grey"> © Shamollift tashkiloti shamollift.uz</p>
    </div>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
.footer{
  padding: 20px 50px;
}

.grey{
  background-color: #3E3E3E;
}

a{
  color: white;
  text-decoration: none;
}

.links-and-img{
  width: 100%;
}
hr{
  margin: 10px 0;
  width: 100%;
  background-color: #626262;
}
</style>