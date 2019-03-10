<template>
  <v-app>
    <v-toolbar app>
      <v-flex style="display: flex; align-items: center; justify-content: center; width: 100%;">
        <i class="fa fa-bars" style="flex: 0;"></i>
        <v-flex align-center justify-center d-flex>
          <v-img
            max-width="130"
            :src="require('./assets/firebrand-logo.png')"
          />
        </v-flex>
      </v-flex>
      <v-spacer></v-spacer>
    </v-toolbar>

    <v-content>
      <router-view/>
    </v-content>
  </v-app>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      //
    };
  },
};
</script>
