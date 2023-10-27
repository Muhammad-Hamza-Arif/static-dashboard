<template>
  <v-app>
    <v-navigation-drawer app>
      <SideBar/>
    </v-navigation-drawer>

    <v-app-bar app>
      <NavBar/>
    </v-app-bar>

    <v-main>
      <v-container class="d-flex align-center justify-center" style="min-height: 300px;">
        <RouterView/>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import SideBar from '../components/SideBar.vue';
import NavBar from '../components/NavBar.vue';

export default {
  name: "HelloWorld",
  components: {
    SideBar,
    NavBar
  }
};
</script>

<style  scoped>
/* Add your custom styles here */
</style>
