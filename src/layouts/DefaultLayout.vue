<template>
    <v-layout row wrap>
        <v-toolbar scroll-off-screen app dark>
            <span class="headline font-weight-light primary--text">iTax PRO</span>
            <v-spacer></v-spacer>
            <v-btn flat small color="primary">HOME</v-btn>
            <v-btn flat small color="primary">LOGIN</v-btn>            
            <v-btn flat small color="primary">Sign-up</v-btn>
            <v-btn outline small color="primary">ABOUT</v-btn>
        </v-toolbar>
        <v-container fluid>
            <router-view></router-view>
        </v-container>
        <v-footer dark app>
            <v-layout row wrap pa-2>
                <span class="caption font-italic">
                    Centralized Cloud Computing International Inc.  
                </span>
                <v-spacer></v-spacer>
                <span class="caption font-italic">
                   ©2019 CCCI Inc. All rights reserved.
                </span>
            </v-layout>
        </v-footer>
    </v-layout>
</template>

<script>
export default {

}
</script>

<style>

</style>
