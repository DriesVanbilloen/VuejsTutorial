<template>
  <v-container>
      <v-layout row wrap>
          <v-flex xs12>
              <v-card>
                  <v-card-title><h6>Meetups</h6></v-card-title>
                  <v-card-media
                  src="https://upload.wikimedia.org/wikipedia/commons/7/7a/Paris_-_Blick_vom_gro%C3%9Fen_Triumphbogen.jpg"
                  height ="400px"
                  >
                  </v-card-media>
                  <v-card-text>
                      <div class="info--text">17th July 2018 - Paris France</div>
                      <div>This is the meetup for Paris. We visit almost all the monuments in Paris like the eifel tower etc. Make sure to get your tickets online</div>
                  </v-card-text>
                  <c-card-actions>
                      <v-spacer></v-spacer>
                      <v-btn class="primary">Register Here</v-btn>
                  </c-card-actions>
              </v-card>
          </v-flex>
      </v-layout>
  </v-container>
</template>
