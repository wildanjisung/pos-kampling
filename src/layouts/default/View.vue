<template>
  <v-app id="inspire">
    <!-- <AppBar /> -->
    <v-main class="bg-grey-lighten-3">
      <v-container>
        <v-row>
          <v-col class="d-none d-md-block" cols="12" md="2">
            <v-sheet rounded="lg" min-height="268">
              <!--  -->
            </v-sheet>
          </v-col>

          <v-col cols="12" md="8">
            <router-view />
          </v-col>

          <v-col class="d-none d-md-block" cols="13" md="2">
            <v-sheet rounded="lg" min-height="268">
              <!--  -->
            </v-sheet>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
    <NavBottom />
  </v-app>
</template>

<script setup>
import AppBar from "@/components/nav/AppBar.vue";
import NavBottom from "@/components/nav/NavBottom.vue";
</script>
