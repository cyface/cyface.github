<template>
  <v-layout justify-center>
    <v-flex xs12 sm9 md7>
      <v-card color="secondary" class="mt-4 elevation-24">
        <v-layout row>
          <v-flex xs12 md6>
            <v-card-title class="white--text text-xs-center text-sm-left">
              <v-flex>
                <div class="headline">Tim L. White</div>
                <v-divider></v-divider>
                <div>Principal Engineer</div>
                <v-img src="timlwhite.jpg" cover class="ma-1 mt-3 elevation-5 hidden-sm-and-up"></v-img>
              </v-flex>
            </v-card-title>
            <div class="mx-3">
              <p>With over 25 years of experience designing and building Enterprise-scale systems from eCommerce to Content Management, as well as Embedded Systems for Aerospace,
                Tim is able to connect business and technology to solve the most challenging problems. </p>
              <p>
                Specializing in end-to-end content management systems, including editorial process, optimized content delivery and SEO performance,
                data-driven content, and rapid development to rich content tool-kits for content teams, Tim has delivered Fortune 100 websites in a variety of roles.
              </p>
              <p>
                Tim started Cyface Design to offer consulting for universities, small businesses, and non-profits to help them jump-start crucial projects.
              </p>
              <p>
                From designing a modular satellite training system structure and firmware, to modernizing and deploying massive college web applications, to building document workflows for government agencies,
                Tim has experience listening to what people really need, and designing end-to-end solutions that last for decades.
              </p>
              <p>
                If you need advice on how to move past analysis paralysis and actually executing your vision, Cyface Design is available to help.
              </p>
              <p>
                Contact Cyface Design via the button below to get started, or check out our <router-link to="portfolio">Portfolio</router-link> to learn more.
              </p>
            </div>
          </v-flex>
          <v-flex class="xs6 hidden-xs-only">
            <v-img src="timlwhite.jpg" cover class="my-3 mr-3 elevation-5"></v-img>
          </v-flex>
        </v-layout>
        <v-divider light></v-divider>
        <v-card-actions class="pa-3">
          <v-btn large class="mx-auto" href='https://www.linkedin.com/in/timlwhite?trk=profile-badge'>
            <v-layout justify-space-between align-center row fill-height>
              <v-flex xs12 style="font-size: 17.5px; line-height: 21px; text-transform: none; color: #000">Contact me via&nbsp;&nbsp;</v-flex>
              <v-flex xs12>
                <v-img alt="LinkedIn Logo" height="21px" width="93px" src="https://static.licdn.com/scds/common/u/images/logos/linkedin/logo_linkedin_93x21_v2.png"/>
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
