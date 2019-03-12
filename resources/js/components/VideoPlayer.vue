<template>
    <div>
        <v-card>
            <v-responsive :aspect-ratio="16/9">
                <v-card-text>
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/gZUSFda_W7k" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </v-card-text>
            </v-responsive>
        </v-card>
    </div>
</template>

<script>
    export default {
        name: "VideoPlayer"
    }
</script>

<style scoped lang="scss">

</style>
