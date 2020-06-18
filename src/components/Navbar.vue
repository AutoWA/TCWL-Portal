<template>
  <v-app-bar app color="primary" dark>
    <div class="d-flex align-center">
      <v-img
        alt="Vuetify Logo"
        class="shrink mr-2"
        contain
        src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
        transition="scale-transition"
        width="40"
      />

      <v-img
        alt="Vuetify Name"
        class="shrink mt-1 hidden-sm-and-down"
        contain
        min-width="100"
        src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
        width="100"
      />
    </div>
    <v-tabs>
      <v-tab to="/">Home</v-tab>
      <v-tab>Faculty</v-tab>
      <v-tab to="/about">About</v-tab>
    </v-tabs>
    <v-spacer></v-spacer>

    <v-btn href="http://47.92.91.148" target="_blank" text>
      <span class="mr-2">童创未来OJ平台</span>
      <v-icon>mdi-open-in-new</v-icon>
    </v-btn>
  </v-app-bar>
</template>

<script>
export default {
  name: "Navbar",
  data: () => ({})
};
</script>
