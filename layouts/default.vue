<template>
  <v-app dark>
    <v-app-bar
      :clipped-left="clipped"
      fixed
      app
      color="indigo lighten-5"
    >
      <nuxt-link to="/"><img height="20px" src="~/assets/images/squirrel.png"></nuxt-link>
      <span style="margin:0 0 0 auto">
        <a href="https://github.com/0daryo"
        target="_blank"
        title="0daryorのGitHubページを開く"
        >
      <img height="20px" src="~/assets/images/GitHub_Logo.png">
      </a>
      <a href="https://twitter.com/0daryo?ref_src=twsrc%5Etfw" class="twitter-follow-button" data-show-count="false">Follow @0daryo</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 
      <a href="https://qiita.com/0daryo" target="_blank" style="background-color:white;">
            <img height="20px" src="~/assets/images/qiita-favicon.png">
      </a>
      <a href="https://0daryo.hatenablog.com/" target="_blank">
            <img height="20px" src="~/assets/images/hatenablog-logotype.svg">
      </a>
      </span>
    </v-app-bar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    <v-navigation-drawer
      v-model="rightDrawer"
      :right="right"
      temporary
      fixed
    >
      <v-list>
        <v-list-item @click.native="right = !right">
          <v-list-item-action>
            <v-icon light>
              mdi-repeat
            </v-icon>
          </v-list-item-action>
          <v-list-item-title>Switch drawer (click me)</v-list-item-title>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-footer
      :fixed="fixed"
      app
    >
      <span>&copy; 2019</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: '0daryo'
    }
  }
}
</script>
