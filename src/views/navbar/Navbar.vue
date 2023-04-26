<template>
    <div><v-icon icon="mdi-vuetify"></v-icon>
        <v-card max-width="448" class="mx-auto" color="grey-lighten-3">
            <v-layout>
                <v-app-bar color="teal-darken-4">
                    <template v-slot:image>
                        <v-img gradient="to top right, rgba(19,84,122,.8), rgba(128,208,199,.8)"></v-img>
                    </template>

                    <template v-slot:prepend>
                        <v-app-bar-nav-icon></v-app-bar-nav-icon>
                    </template>

                    <v-app-bar-title>Inicio</v-app-bar-title>
                    <v-icon icon="fa:fas fa-lock"></v-icon>
                    <v-icon icon="mdi-home" />
                    <v-icon icon="mdi-vuetify"></v-icon>
                    <v-icon icon="fas fa-plus" /> 
                    <v-icon icon="mdi:mdi-minus" />


                    <v-spacer></v-spacer>

                    <v-icon icon="mdi-vuetify"></v-icon>

                    <v-btn icon>
                        <v-icon>mdi-heart</v-icon>
                    </v-btn>

                    <v-btn icon>
                        <v-icon>mdi-dots-vertical</v-icon>
                    </v-btn>
                </v-app-bar>

                <!-- <v-main>
                    <v-container fluid>
                        <v-row dense>
                            <v-col v-for="n in 4" :key="n" cols="12">
                                <v-card :title="`Content ${n}`" :subtitle="`Subtitle for Content ${n}`"
                                    text="Lorem ipsum dolor sit amet consectetur, adipisicing elit.?"></v-card>
                            </v-col>
                        </v-row>
                    </v-container>
                </v-main> -->
            </v-layout>
        </v-card>
    </div>
</template>

<script setup lang="ts">

</script>

<style></style>