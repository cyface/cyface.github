<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-flex
      xs12
      sm8
      md6
    >
      <div class="text-xs-center">
      </div>
      <v-card>
        <v-card-title class="headline">Cyface Design</v-card-title>
        <v-card-text>
          <h3>Portfolio</h3>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" flat nuxt to="/portfolio">Check it out!</v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>

export default {
  components: {
  }
}
</script>
