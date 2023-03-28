<template>
  <v-app :style="{ background: $vuetify.theme.themes.dark.background }">
    <Navbar />
    <v-container fluid>
      <v-col cols="6">
        <v-img src="1.jpg" contain max-height="500"></v-img>
      </v-col>
      <v-col cols="6">
        <h5 class="red--text text-darken-4"></h5>
      </v-col>
    </v-container>
  </v-app>
</template>

<script>
  import Navbar from '../components/Navbar'

  export default {
    name: 'Home',

    components: {
      Navbar,
    },
  }
</script>
