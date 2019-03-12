<template>
    <v-toolbar
        color="indigo"
        fixed
        clipped-left
        app
    >
        <v-toolbar-side-icon @click.stop="drawer = !drawer"></v-toolbar-side-icon>
        <v-icon class="mx-3">fab fa-youtube</v-icon>
        <v-toolbar-title class="mr-5 align-center">
            <span class="title">BlueTube</span>
        </v-toolbar-title>
        <v-spacer></v-spacer>
        <v-layout row align-center style="max-width: 650px">
            <v-text-field
                :append-icon-cb="() => {}"
                placeholder="Find more sadness..."
                single-line
                append-icon="search"
                color="white"
                hide-details
            ></v-text-field>
        </v-layout>
    </v-toolbar>
</template>

<script>
    export default {
        name: "Mast"
    }
</script>

<style scoped>

</style>
