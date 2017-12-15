<template>
    <v-container>
        <v-layout row wrap>
            <v-flex xs12 sm10 md8 offset-sm1 offset-md2 >
                <v-card class="info">
                    <v-container fluid>
                        <v-layout row>
                            <v-flex xs6 sm4 md2>
                                <v-card-media
                                src="https://upload.wikimedia.org/wikipedia/commons/7/7a/Paris_-_Blick_vom_gro%C3%9Fen_Triumphbogen.jpg"
                                height="160px"
                                contain
                                ></v-card-media>
                            </v-flex>
                            <v-flex xs7 sm8 md9>
                                <v-card-title primary-title>
                                    <div>
                                        <h5 class="white--text">My Meetup</h5>
                                        <div>17th July 2018</div>
                                    </div>
                                </v-card-title>
                                <v-card-actions>
                                    <v-btn flat to="/meetups/1">
                                        <v-icon left light>arrow_forward</v-icon>
                                        ViewMeetup
                                    </v-btn>
                                </v-card-actions>
                            </v-flex>
                        </v-layout>
                    </v-container>
                </v-card>
            </v-flex>
        </v-layout>
    </v-container>
</template>