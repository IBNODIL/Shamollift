<script>
import { RouterLink, RouterView } from 'vue-router'

export default {
  data: () => ({
    drawer: false,
    group: null,
  }),
  watch: {
    group () {
      this.drawer = false
    },
  },
}
</script>

<template>
  <v-app class="bg">
    <v-layout>
      <v-app-bar class="bg">
        <v-toolbar-title class="mx-6 logo"><a href="#"><img height="40" src="./assets/img/logo.png" alt=""></a></v-toolbar-title>

        <div class="hidden-sm-and-down">
          <v-list class="hidden-sm-and-down links mx-16 bg d-flex">
          <v-list-item class="hidden-sm-and-down">
            <v-btn class="hidden-sm-and-down"><a href="/#about-company">О Компании</a></v-btn>
          </v-list-item>

          <v-list-item class="hidden-sm-and-down">
            <v-btn class="hidden-sm-and-down"><a href="/#products">Продукция</a></v-btn>
          </v-list-item>

          <v-list-item class="hidden-sm-and-down">
            <v-btn class="hidden-sm-and-down"><a href="/#advantages">Услуги</a></v-btn>
          </v-list-item>

          <v-list-item class="hidden-sm-and-down">
            <v-btn class="hidden-sm-and-down linear-gradient-btn text-black">Bog'lanish</v-btn>
          </v-list-item>
        </v-list>
        </div>

        <v-app-bar-nav-icon class="hidden-md-and-up" variant="text" @click.stop="drawer = !drawer"></v-app-bar-nav-icon>
      </v-app-bar>

      <v-navigation-drawer
        v-model="drawer"
        location="right"
        temporary
        class="bg"
      >
        <v-list class="d-flex flex-column align-center">
          <v-list-item>
            <v-btn class="bg"><a href="#about-company">О Компании</a></v-btn>
          </v-list-item>

          <v-list-item>
            <v-btn class="bg">Продукция</v-btn>
          </v-list-item>

          <v-list-item>
            <v-btn class="bg">Услуги</v-btn>
          </v-list-item>

          <v-list-item>
            <v-btn class="linear-gradient-btn text-black">Bog'lanish</v-btn>
          </v-list-item>
        </v-list>
      </v-navigation-drawer>

      <v-main>
        <RouterView></RouterView>
      </v-main>
    </v-layout>
  </v-app>
</template>

<style scoped>
a{
  text-decoration: none;
  color: white;
}
.bg{
  background-color: #111111;
  color: white;
}

.linear-gradient-btn{
  background: linear-gradient(140deg, #5C5C5C 1.86%, #CDCBCB 44.24%, #5C5C5C 96.52%);
}
</style>
