<template>
  <v-app>
    <v-navigation-drawer v-model="sideNav">

    </v-navigation-drawer>
    <v-toolbar>
      <v-toolbar-title>DevMeetup</v-toolbar-title>
    <v-toolbar-side-icon @click="sideNav = !sideNav"></v-toolbar-side-icon>
      <v-spacer></v-spacer>
      <v-toolbar-items>
        <v-btn flat>
          <v-icon left>supervisor_account</v-icon>
          view meetups
        </v-btn>
      </v-toolbar-items>
    </v-toolbar>
    <main>

    </main>  
  </v-app>
</template>

<script>
  export default {
    data () {
      return {
        sideNav: false
      }
    }
  }

</script>
