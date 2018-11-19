<template>
  <v-container>
    <v-layout justify-center>
      <v-flex xs12 md6>
        <v-card md4>
          <v-card-title primary-title>
            <h1 class="display-1 font-weight-bold mb-3">Register Page</h1>
          </v-card-title>
          <v-card-text>
            <v-text-field
            label="Email address"
            type="Email"
            ></v-text-field>
            <v-text-field
            label="Password"
            type="Password"
            ></v-text-field>
            <v-text-field
            label="Password"
            type="Password"
            ></v-text-field>
          </v-card-text>
          <v-divider></v-divider>
          <v-card-actions>
            <v-btn color="primary" depressed block>Register</v-btn>
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
