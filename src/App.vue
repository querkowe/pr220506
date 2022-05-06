<template>
  <v-app>
    <v-navigation-drawer
      v-model="drawer1"
      app
    >
      <!--  -->
      
    </v-navigation-drawer>
    <v-system-bar
      app
      color="primary"
      dark
      height="50"
    >
      <div class="d-flex align-center">
        <h1>
          Head
        </h1>
      </div>
    </v-system-bar>
    <v-navigation-drawer
      v-model="drawer2"
      app
      right
    ></v-navigation-drawer>

    <v-main>
      <Main/>
    </v-main>
  </v-app>
</template>

<script>
import Main from './components/Main';

export default {
  name: 'App',

  components: {
    Main,
  },

  data: () => ({
    //
  }),
};
</script>
