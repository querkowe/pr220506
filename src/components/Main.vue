<template>
  <div>
    <v-app-bar
      app
      dark
    >
      <v-app-bar-nav-icon @click="drawer1 = !drawer1"></v-app-bar-nav-icon>

      <div class="d-flex align-center">
        <h3>
          Body
        </h3>
      </div>

      <v-spacer></v-spacer>

      <v-app-bar-nav-icon @click="drawer2 = !drawer2"></v-app-bar-nav-icon>

    </v-app-bar>
    <v-container>
      <TestCarousel/>
    </v-container>
    <v-container>
      <TestCards1/>
    </v-container>
  </div>
</template>

<script>
import TestCarousel from "./content/TestCarousel.vue"
import TestCards1 from "./content/TestCards1.vue"
  export default {
    name: "HelloWorld",
    data: () => ({
      drawer1: null,
      drawer2: null
    }),
    components: { TestCarousel, TestCards1 }
}
</script>
