<template>
  <div id="app">
    <app-main></app-main>
    
  </div>
</template>

<script>
import Main from './components/Main.vue'

export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components:{
    'app-main': Main,
  }
}
</script>

<style lang="scss">

*,
*::before,
*::after{
  margin: 0px;
  padding: 0px;
}

html{
  font-size: 62.5%;
}

</style>
