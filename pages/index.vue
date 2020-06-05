<template>
  <div>
    <v-container >
      <v-row>
        <v-col class="d-flex justify-center" >  
          <span class="display-2" style="font-family: 'Montserrat' !important " >Maghfurin, M.</span>
        </v-col>
      </v-row>
      <v-row>
        <v-col class="d-flex justify-center"  >  
          <v-btn color="primary" class="mx-2" to="/" ><v-icon>mdi-file-document-edit</v-icon> Blog</v-btn>
          <v-btn color="primary" class="mx-2" to="/about" ><v-icon class="mr-1" >mdi-card-account-details</v-icon> About Me</v-btn>
          <a href="https://github.com/maghffu"><v-btn color="primary" class="mx-2" ><v-icon>mdi-github</v-icon> Github</v-btn></a>
        </v-col>
      </v-row>
      <v-row class="mt-2" >
        <v-col cols="2" ></v-col>
        <v-col cols="8" style="background: #f5f5f5" >

        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
  export default {

  }
</script>
