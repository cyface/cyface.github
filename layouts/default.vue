<template>
  <v-app>
    <v-navigation-drawer v-model="drawer" app disable-resize-watcher>
      <v-list>
        <v-list-tile v-for="(item, i) in items" :key="i" :to="item.to" router exact>
          <v-list-tile-action>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-tile-action>
          <v-list-tile-content>
            <v-list-tile-title v-text="item.title" />
          </v-list-tile-content>
        </v-list-tile>
      </v-list>
    </v-navigation-drawer>
    <v-toolbar fixed app color="primary" class="white--text">
      <v-toolbar-side-icon @click="drawer = !drawer" dark />
      <v-spacer></v-spacer>
        <v-img src="CyfaceLogoNoShadow.png" height="55" contain></v-img>
      <v-spacer></v-spacer>
    </v-toolbar>
    <v-content style="background-color: #373634; background-image: url('abstract-circuit-board-background-texture-497178504_4618x3694.jpeg'); background-size: cover; background-position: right center;">
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    <v-footer app height="auto" color="primary" class="white--text">
      <v-flex text-xs-center>&copy;2019 Cyface Design</v-flex>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      drawer: false,
      items: [
        {
          icon: 'apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'bubble_chart',
          title: 'Portfolio',
          to: '/portfolio'
        }
      ]
    }
  }
}
</script>
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     
