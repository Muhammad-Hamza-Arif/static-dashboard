<template>
    <v-app>
    <v-navigation-drawer class="bg-deep-purple" app >
      <v-list class="text-center mt-15">
        <v-list-item link to="/dashboard">
          <v-list-item-title>Dashboard</v-list-item-title>
        </v-list-item>
        <v-list-item link to="/account">
          <v-list-item-title>Account</v-list-item-title>
        </v-list-item>
        <v-list-item link to="/admin">
          <v-list-item-title>Admin</v-list-item-title>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
</v-app>
</template>

<script>
export default {
  name: "SideBar",
};
</script>

<style lang="scss" scoped></style>
