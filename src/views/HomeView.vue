<script setup>
  import Company from '../components/Company.vue';
  import Advantages from '../components/Advantages.vue';
  import OurProjects from '../components/OurProjects.vue';
  import SocialCites from '../components/SocialCites.vue';
</script>

<template>
  <v-app>
    <div class="hero">
      <v-card class="hero-card">
        <v-card-title class="pa-0 ma-0 my-2">
          <span class="pa-0 ma-0 text-h3">Shamollift</span>
        </v-card-title>
        <p>
          Мы предоставляем нашим клиентам самое современное лифтовое оборудование и полный спектр услуг от проектирования до ремонта пассажирских, кухонных, строительных, автомобильных и грузовых лифтов, а также эскалаторов.
        </p>
        
        <v-btn class="mt-3 v-btn--size-small linear-gradient-btn text-black">Hoziroq bog’laning <v-icon class="mx-1">mdi-arrow-right</v-icon></v-btn>
      </v-card>
    </div>

    <div id="about-company" class="bg py-10 about-company">
      <Company></Company>
    </div>

    <div id="products" class="bg py-10 our-projects">
      <OurProjects></OurProjects>
    </div>

    <div id="advantages" class="bg py-10 advantages">
      <Advantages></Advantages>
    </div>

    <div class="grey-bg py-10 social-ciets">
      <SocialCites></SocialCites>
    </div>
  </v-app>
</template>

<style scoped>
.bg{
  background: #111;
}
.hero{
  background-image: url(../assets/img/hero_big_format_1.png);
  background-repeat: no-repeat;
  min-height: 70vh;
  background-size: cover;
}

.grey-bg{
  background: #3E3E3E;
}

.hero-card{
  color: #FFF;
  padding: 20px;
  width: 600px;
  position: absolute;
  left: 202px;
  top: 105px;
  border-radius: 20px;
  background: rgba(255, 255, 255, 0.15);
  backdrop-filter: blur(5px);
}

.linear-gradient-btn{
  background: linear-gradient(140deg, #5C5C5C 1.86%, #CDCBCB 44.24%, #5C5C5C 96.52%);
}

@media screen and (max-width: 960px) {
  .hero-card{
    min-height: 70%;
    top: 0;
    width: 90%;
    margin: 50px auto;
    position: relative;
    left: 0;
  }
}
</style>