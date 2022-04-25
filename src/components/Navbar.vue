<template>
<nav>
    <v-app-bar app color="#134b8a" dark>
        <v-toolbar-title>
            <v-img alt="Vuetify Logo" class="shrink mr-2" contain src="../assets/ics.jpg" transition="scale-transition" width="50" />
        </v-toolbar-title>

        <v-spacer></v-spacer>
        <v-img class="shrink mr-2" width="40" src="../assets/art.jpg" />
        <span>Sarawut Boonruang</span>
    </v-app-bar>
    <v-navigation-drawer app v-model="drawer">
         <v-img alt="Vuetify Logo" class="shrink mr-2" contain src="../assets/ics.jpg" transition="scale-transition" width="100" />
    </v-navigation-drawer>
</nav>
</template>

<script>
export default {
    data() {
        return {
            drawer: true
        }
    }
}
</script>
