<template>
  <div id="content" class="app-content box-shadow-z0" role="main">  
    <dropit-navbar></dropit-navbar>
    <dropit-rendermain></dropit-rendermain>
  </div>
</template>

<script>
import navbarcomponent from './components/navbar/navbar'
import rendermaincomponent from './components/rendermain/rendermain'

export default {
  name: 'content',
  data () {
    return {
      msg: 'Welcome to Your dropitblog App'
    }
  },
  components: {
      'dropit-navbar':navbarcomponent,
      'dropit-rendermain': rendermaincomponent
  }
}
</script>

<style scoped>

</style>
