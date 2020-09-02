<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <div class="d-flex align-center">
        <h2>Crtv-fm app</h2>
      </div>

      <v-spacer></v-spacer>

      <v-btn href="http://www.crtv.cm/crtv-yaounde-fm94/" target="_blank" text>
        <span class="mr-2">Official website</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>
    <VideoConference />
  </v-app>
</template>

<script>
import VideoConference from "./components/VideoConference";

export default {
  name: "App",

  components: {
    VideoConference,
  },

  data: () => ({
    //
  }),
};
</script>
