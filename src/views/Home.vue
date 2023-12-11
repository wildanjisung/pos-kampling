<template>
  <v-row>
    <v-col cols="12">
      <CarouselView />
    </v-col>
  </v-row>
  <v-row>
    <v-col cols="12">
      <MenuView />
    </v-col>
  </v-row>
</template>

<script setup>
import HelloWorld from "@/components/HelloWorld.vue";
import CarouselView from "@/components/CarouselView.vue";
import MenuView from "@/components/MenuView.vue";
</script>
