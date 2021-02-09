<template>
    <v-container fluid fill-height class="home-hero" style="max-height:100vh;">
        <v-layout justify-center align-center column pa-5>
            <div class="display-4 font-weight-black gray--text text-xs-center">
                DATA VISUALISATIONS
            </div>
            <div class="display-1 font-weight-bold gray--text text-xs-center">
                Exploring data visualisations with Chart.js and D3.js
            </div>
            <v-btn fab class="mt-5 red darken-4">
                <v-icon large color="white">*</v-icon>
            </v-btn>
        </v-layout>
    </v-container>
</template>

<script>
export default {
    name: 'HomeHero'
};
</script>

<style scoped>
.home-hero {
    background: url('https://unsplash.com/photos/n6B49lTx7NM');
    background-size: cover;
    width: 100%;
    height: 100%;
}
</style>
