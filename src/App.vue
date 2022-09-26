<template>
  <v-app>
    <v-app-bar
      app
      elevation="0"
    >
      <div class="d-flex align-center">
        <v-img
          alt="Futec Logo"
          class="shrink mr-2"
          contain
          src="./assets/logosimbolo_color@2x.png"
          transition="scale-transition"
          width="100"
        />
      </div>

      <v-spacer></v-spacer>

    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
