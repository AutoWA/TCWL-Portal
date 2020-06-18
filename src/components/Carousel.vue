<template>
  <v-carousel
    cycle
    height="400"
    interval="5000"
    delimiter-icon="mdi-minus"
    hide-delimiter-background
    show-arrows-on-hover
  >
    <v-carousel-item
      v-for="(image, i) in carouselImages"
      :key="i"
      :src="image.src"
      reverse-transition="fade-transition"
      transition="fade-transition"
    >
    </v-carousel-item>
  </v-carousel>
</template>

<script>
export default {
  name: "Carousel",
  data: () => ({
    carouselImages: [
      { src: require("@/assets/carousel_image/1.jpg") },
      { src: require("@/assets/carousel_image/2.jpg") },
      { src: require("@/assets/carousel_image/3.jpg") },
      { src: require("@/assets/carousel_image/4.jpg") },
      { src: require("@/assets/carousel_image/5.jpg") },
      { src: require("@/assets/carousel_image/6.jpg") }
    ]
  })
};
</script>

<style scoped></style>
