<template>
  <v-app>
    <HelloWorld></HelloWorld>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data () {
    return {
      clipped: false,
      drawer: true,
      fixed: false,
      items: [{
        icon: 'bubble_chart',
        title: 'Assetchain Wizard'
      }],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Assetchain Wizard'
    }
  }
}
</script>
