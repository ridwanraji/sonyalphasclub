<template>
  <v-app>
    <v-toolbar
      app
      :clipped-left="clipped"
    >
      <v-toolbar-title v-text="title"></v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items>
        <v-btn
        href="https://www.instagram.com/SonyAlphasClub"
        depressed>
          Home
        </v-btn>
        <v-btn
        href="https://www.instagram.com/SonyAlphasClub"
        depressed>
          Challenges
        </v-btn>
        <v-btn
        href="https://www.instagram.com/SonyAlphasClub"
        depressed>
          Blog
        </v-btn>
        <v-btn
        href="https://www.instagram.com/SonyAlphasClub"
        depressed>
          Photo Submission
          <v-icon right dark>cloud_upload</v-icon>
        </v-btn>
      </v-toolbar-items>
    </v-toolbar>
    <v-content>
      <router-view/>
    </v-content>
    <v-footer :fixed="fixed" app>
      <span>&copy; 2017</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      clipped: false,
      drawer: true,
      fixed: false,
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'SonyAlphasClub'
    }
  },
  name: 'App'
}
</script>
