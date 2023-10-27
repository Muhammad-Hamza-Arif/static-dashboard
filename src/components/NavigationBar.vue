<template>
  <v-app-bar :elevation="0" rounded>
    <v-app-bar-nav-icon />
    <template v-slot:append>
      <v-btn icon="mdi-heart"></v-btn>

      <v-btn icon="mdi-magnify"></v-btn>

      <v-btn icon="mdi-dots-vertical"></v-btn>
    </template>
  </v-app-bar>
</template>

<script>
export default {
  name: "NavigationBar",
};
</script>

<style lang="scss" scoped></style>
