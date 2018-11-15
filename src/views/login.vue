<template>
  <v-container>
    <v-layout
    text-md-center
    wrap
    >
    <v-flex md4>
      <v-card>
        <v-card-title primary-title>
        <h1 class="display-1 font-weight-bold mb-3">Login Page</h1>
        </v-card-title>
        <v-card-text>
          <v-text-field
          label="Email address"
          ></v-text-field>
          <v-text-field
          label="Password"
          ></v-text-field>
      </v-card-text>
      <v-divider></v-divider>
      <v-card-actions>
        <v-btn color="primary" depressed block @click="onAdd()">Login</v-btn>
      </v-card-actions>
    </v-card>
  </v-flex>

</v-layout>
</v-container>
</template>

<script>
</script>

<style>
</style>
