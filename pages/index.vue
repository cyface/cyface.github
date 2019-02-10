<template>
  <v-layout justify-center align-center>
    <v-flex xs12 sm9 md7>
      <v-card color="secondary" class="mt-4 elevation-24">
        <v-layout row>
          <v-flex xs6>
            <v-card-title class="white--text">
              <div>
                <div class="headline">Tim L. White</div>
                <v-divider></v-divider>
                <div>Principal Engineer</div>
              </div>
            </v-card-title>
            <v-content class="ma-3">
              <p>With over 25 years of experience designing and building Enterprise-scale systems from eCommerce to Content Management, as well as Embedded Systems for Aerospace,
              Tim is able to connect business and technology to solve the most challenging problems. </p>
              <p>
                Specializing in end-to-end content management systems, including editorial process, optimized content delivery and SEO performance,
                data-driven content, and rapid development to rich content toolkits for conrtent teams, Tim has delivered Fortune 100 websites in a variety of roles.
              </p>
            </v-content>
          </v-flex>
          <v-flex xs6>
            <v-img src="timlwhite.jpg" contain postition="center top" class="my-3 mr-3 elevation-5"></v-img>
          </v-flex>
        </v-layout>
        <v-divider light></v-divider>
        <v-card-actions class="pa-3">
          <v-btn large class="mx-auto" href='https://www.linkedin.com/in/timlwhite?trk=profile-badge'>
              <v-layout row class="mt-2">
                <v-flex xs6>Contact me via</v-flex>
                <v-flex xs6>
                  <img class="ml-4" alt="LinkedIn Logo" height="21px" width="93px" src="https://static.licdn.com/scds/common/u/images/logos/linkedin/logo_linkedin_93x21_v2.png"/>
                </v-flex>
              </v-layout>
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>

  export default {
    components: {}
  }
</script>
