<template>
  <v-app>
    <v-toolbar>
      <v-toolbar-side-icon></v-toolbar-side-icon>
      <v-toolbar-title>Jit Web</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn flat to="/">Home</v-btn>
        <v-btn flat to="/register">Register</v-btn>
        <v-btn flat to="/login">Login</v-btn>
      </v-toolbar-items>
    </v-toolbar>

    <v-content>
      <router-view/>

    </v-content>
  </v-app>
</template>
