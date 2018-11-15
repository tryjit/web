<template>
  <v-container>
    <v-layout
    text-md-center
    wrap
    >
      <HelloWorld msg="Welcome to Your Vue.js App"/>
    </v-layout>
  </v-container>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>
