<template>
       <v-toolbar app fixed dark color="primary">
            <v-toolbar-title><v-btn flat class="text-capitalize" to="/">Rumis</v-btn></v-toolbar-title>
            <v-spacer></v-spacer>
            <v-toolbar-items class="hidden-sm-and-down"> 
                <v-btn flat class="text-capitalize" to="/login">Login</v-btn>
                <v-btn flat class="text-capitalize">Register</v-btn>
                <v-btn flat class="text-capitalize">Test</v-btn>

          
        </v-toolbar-items>
                
      </v-toolbar>
</template>

<style>

</style>

<script>
export default {
    name: 'navigations',
    data (){
        return {
          
        }
    }
}
</script>


