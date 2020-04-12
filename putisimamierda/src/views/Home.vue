<style>
.myfont {
  font-size: 20px;
  font-family: 'Ubuntu Mono', monospace;
}
</style>

<template>
  <v-container fluid class="accent" style="height:2000px">
    <v-layout wrap>
      <v-flex class="primary" xs12>
        <h1>12</h1>
      </v-flex>
      <v-flex class="secondary" xs6>
        <h1>12</h1>
      </v-flex>
      <v-flex class="error" xs6>
        <h1>12</h1>
      </v-flex>
    </v-layout>
    <v-layout class="mt-5 secondary" justify-center style="height:500px">
      <v-flex class="blue-grey darken-3 white--text" xs3>
        <h1>Hola</h1>
      </v-flex>
      <v-flex class="accent" xs3>
        <h1>Hola2</h1>
      </v-flex>
    </v-layout>
    <v-layout>
      <v-flex>
        <h1 class="myfont">System flags submitted (last 30 days).</h1>
        <h1 class="display-1 text-md-center">Lorem, ipsum dolor.</h1>
        <h1 class="display-4">Lorem, ipsum dolor.</h1>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>

export default {
}
</script>
