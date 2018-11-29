<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <jumbotron/>
      <card-group-menu />
    </v-flex>
  </v-layout>
</template>

<script>
/* eslint-disable no-console */
import CardGroupMenu from '~/components/CardGroupMenu.vue'
import Jumbotron from '~/components/Jumbotron.vue'


export default {
  components: {
    CardGroupMenu,
    Jumbotron,
  }
}
</script>
