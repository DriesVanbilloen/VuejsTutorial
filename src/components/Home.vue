<template>
    <v-container>
        <v-layout row wrap class="mb-2">
            <v-flex xs12 sm6 class="text-xs-center text-sm-right">
                <v-btn large router to="/meetups" class="info">Exploere Meetups</v-btn>
            </v-flex>
            <v-flex xs12 sm6 class="text-xs-center text-sm-left">
                <v-btn large router to="/meetup/new" class="info">Organize Meetup</v-btn>
            </v-flex>
        </v-layout>
        <v-layout row wrap class="mt-2">
            <v-flex>
                <v-carousel>
                    <v-carousel-item 
                    v-for="meetup in meetups" 
                    v-bind:src="meetup.imageUrl" 
                    :key="meetup.id">
                    <div class="title">{{meetup.title}}</div>
                    </v-carousel-item>
                </v-carousel>
            </v-flex>
        </v-layout>
        <v-layout row wrap class="mt-2">
            <v-flex xs12 class="text-xs-center">
                <p>Join our awesome meetups!</p>
            </v-flex>
        </v-layout>
    </v-container>
</template>
<!--<script>
    export default {
        data () {
             return {
                meetups: [
                { imageUrl: 'https://upload.wikimedia.org/wikipedia/commons/4/47/New_york_times_square-terabass.jpg', id: 'blablabla123', title: 'Meetup in New York'},
                { imageUrl: 'https://upload.wikimedia.org/wikipedia/commons/7/7a/Paris_-_Blick_vom_gro%C3%9Fen_Triumphbogen.jpg', id: 'blalkfz123', title: 'Meetup In Paris'}
          ]
      }
  }
}
</script> -->
<script>
    export default {
      data () {
        return {
          meetups: [
              {imageUrl: 'https://upload.wikimedia.org/wikipedia/commons/4/47/New_york_times_square-terabass.jpg', id: 'blabla1', title: 'Meetup in New York'},
              {imageUrl: 'https://upload.wikimedia.org/wikipedia/commons/7/7a/Paris_-_Blick_vom_gro%C3%9Fen_Triumphbogen.jpg', id: 'blabla2', title: 'Meetup in Paris'}
          ]
        }
      }
    }
</script>
<style scoped>
    .title {
        position: absolute;
        bottom: 50px;
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        font-size: 2em;
        padding: 20px;

    }
</style>



