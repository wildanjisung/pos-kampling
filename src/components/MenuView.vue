<template>
  <v-sheet class="py-6" rounded="lg">
    <v-row align="center" justify="center">
      <v-col cols="auto" v-for="(menu) in menus" :key="menu.id">
        <button-comp :icon="menu.icon" :color="menu.color" :text="menu.text" />
      </v-col>
    </v-row>
  </v-sheet>
</template>

<script setup>
import { ref } from 'vue';
import ButtonComp from "@/components/ButtonComp.vue";

const menus = ref([
  {
    id: 1,
    icon: 'mdi-shield-home',
    color: 'red-darken-2',
    text: 'Darurat',
  },
  {
    id: 2,
    icon: 'mdi-account-group',
    color: 'green-darken-2',
    text: 'Rapat',
  }
])
</script>
