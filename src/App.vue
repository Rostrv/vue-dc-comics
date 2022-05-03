<template>
  <div id="app">
    <SiteHeader/>
    <SiteMain/>
    <MiddleNav/>    
  </div>
  
</template>

<script>
import SiteHeader from '@/components/site_header.vue'
import SiteMain from '@/components/site_main.vue'
import MiddleNav from '@/components/middle_nav.vue'



export default {
  name: 'App',
  components: {
   SiteHeader,
   SiteMain,
   MiddleNav
  }
}

</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

img{
  width: 100%;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 30px;
}
</style>
