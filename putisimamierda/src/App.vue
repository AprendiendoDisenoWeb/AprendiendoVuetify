<template>
  <v-app>
      <v-app-bar app>
        <v-app-bar-nav-icon @click="visible = !visible"></v-app-bar-nav-icon>
        <v-toolbar-title>Barra de navegación</v-toolbar-title>
      </v-app-bar>

      <!--El app sirve para que aparezca siempre a un lado el menú y el para que apareza o desparezca-->
      <v-navigation-drawer app v-model="visible" dark><!--Se puede con y sin temporary-->
        <h3>Menu vertical</h3>
        <v-layout mt-4 column align-center>
          <v-flex>
            <v-avatar>
              <img src="https://randomuser.me/api/portraits/men/85.jpg" alt="">
            </v-avatar>
          </v-flex>
        </v-layout>
      </v-navigation-drawer>
    <v-content>
      <router-view/>
    </v-content>
  </v-app>
</template>

<script>
//import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  /*components: {
    HelloWorld,
  },*/

  data: () => ({
    visible : true
    //
  }),
};
</script>
