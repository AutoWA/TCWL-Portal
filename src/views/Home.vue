<template>
  <v-container>
    <v-row>
      <v-col cols="12">
        <Carousel />
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
// @ is an alias to /src
import Carousel from "../components/Carousel";

export default {
  name: "Home",
  components: {
    Carousel
  },
  data: () => ({})
};
</script>
