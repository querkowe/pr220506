<template>
  <v-card>
    <v-card-title>test {{num}}</v-card-title>
    <v-card-subtitle>testing</v-card-subtitle>
    <v-card-text>testing the test {{num}}</v-card-text>
  </v-card>
</template>
<script>
export default {
  props: num,
  data() {

  }
}
</script>