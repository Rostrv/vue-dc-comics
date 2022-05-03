<template>
  <div id="app">
    <SiteHeader/>
    <SiteMain/>
    <MiddleNav/> 
    <SiteFooter/>  

  </div>
  
</template>

<script>
import SiteHeader from '@/components/site_header.vue'
import SiteMain from '@/components/site_main.vue'
import MiddleNav from '@/components/middle_nav.vue'
import SiteFooter from '@/components/site_footer.vue'




export default {
  name: 'App',
  components: {
   SiteHeader,
   SiteMain,
   MiddleNav,
   SiteFooter
  }
}

</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

ul{
  padding: 0;
  list-style: none;
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
  
}
</style>
