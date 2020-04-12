<template>
    <v-container fluid class="blue-grey darken-4" style="height:2000px">
        <v-layout justify-center wrap>
            <v-flex xs12> 
                <h1 class="myfont white--text text-md-center">Hola compañeros, esto es una prueba de botones, vamos a ver qué cosas se pueden hacer</h1>
            </v-flex>
        </v-layout>
        <v-layout>
            <v-flex>
                <v-btn color="primary">Boton</v-btn>
                <v-btn dark color="blue">pNE</v-btn>
                <v-btn dark large color="warning">Boton</v-btn>
                <v-btn dark disabled large color="warning">Boton</v-btn>
            </v-flex>
        </v-layout>
        <v-layout>
            <v-flex>
                <v-btn>
                    Favorito
                    <v-icon class="ml-2">favorite</v-icon>
                </v-btn>

                <v-btn color="blue" fab>
                    <v-icon>forum</v-icon>
                </v-btn>

            </v-flex>
        </v-layout>
    </v-container>
</template>

<script>
export default {
    data()
    {
        return {

        };
    }
};
</script>