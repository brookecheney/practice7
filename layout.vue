<template>


<v-app>
<v-navigation-drawer app>Nav </v-navigation-drawer>

<v-toolbar app>Toolbar</v-toolbar>
<v-content>
    <v-container fluid>



        <router-view></router-view>
    </v-container>
    <v-footer app>

    </v-content>
    <v-footer app>Footer</v-footer>
    </v-app>
    </template>
    <script>
    export default {

    }

</script>


<style scoped>



</style>
