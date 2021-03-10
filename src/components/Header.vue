<template>
    <v-app-bar color="white" dense style="padding: 20px; height: fit-content; box-shadow: none;">
        <v-text-field
            solo
            label="Search"
            prepend-inner-icon="search"
            append-icon="mic_none"
            style="padding-top: 20px;"
        ></v-text-field>
        <v-spacer></v-spacer>
        <v-btn depressed class="btn-add"><v-icon medium>add</v-icon> Create New Post</v-btn>
        <v-btn icon>
            <v-icon>mail_outline</v-icon>
        </v-btn>
        <v-btn icon>
            <v-icon>favorite_border</v-icon>
        </v-btn>
        <v-avatar>
            <img src="../assets/profile.jpg" alt="">
        </v-avatar>
        <v-icon medium>arrow_drop_down</v-icon>
    </v-app-bar>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>
.v-app-bar {
    border-bottom: 1px solid blue !important;
}

.btn-add {
    width: fit-content; 
    background: #ff003c !important; 
    color: #FFFFFF !important;
    box-shadow: 0 12px 6px -6px #C0C6CC !important;
}

img {
    max-width: 100%;
    height: 100%;
    object-fit: cover;
}
</style>