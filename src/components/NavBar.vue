<template>
    <v-app>
      <v-app-bar app>
        <v-container >
          <v-layout >
            <v-list class="d-flex justify-center ml-15">
              <v-list-item class="ml-15">
                <v-list-item-title class="ml-15">Home</v-list-item-title>
              </v-list-item>
              <v-list-item class="ml-15">
                <v-list-item-title class="ml-15">About</v-list-item-title>
              </v-list-item>
              <v-list-item class="ml-15">
                <v-list-item-title class="ml-15">Contact Us</v-list-item-title>
              </v-list-item>
            </v-list>
          </v-layout>
        </v-container>
      </v-app-bar>
      <!-- Add the rest of your page content here -->
    </v-app>
  </template>
  

<script>
export default {
  name: "NavBar",
};
</script>

<style lang="scss" scoped></style>
