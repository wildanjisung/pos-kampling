<template>
  <v-btn
    :prepend-icon="icon"
    stacked
    variant="outlined"
    rounded="lg"
    :color="color"
  >
    {{text}}
  </v-btn>
</template>

<script setup>
defineProps({
  icon: String, 
  color: String,
  text: String
});
</script>
