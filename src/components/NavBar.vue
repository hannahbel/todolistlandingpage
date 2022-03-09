<template>
  <v-app-bar app color="#ffffff" light flat class="px-8">
    <v-btn icon>
      <v-icon color="#ea5b38" dark>fas fa-clipboard-list</v-icon>
    </v-btn>

    <v-spacer></v-spacer>
    <v-btn text @click="scroll('home')">Home</v-btn>
    <v-btn text @click="scroll('project')">About</v-btn>
    <v-btn text @click="scroll('about')">App</v-btn>
    <v-btn text @click="scroll('contact')"> Contact</v-btn>
  </v-app-bar>
</template>

<script>
export default {
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
  },
};
</script>

<style>
</style>