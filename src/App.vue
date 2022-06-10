<template>
  <div class="bg-background">
    <div class="">
      <NavBar/>
      <router-view/>
      <Footer/>
    </div>
  </div>
  
</template>
<script>
import NavBar from '@/components/NavBar.vue'
import Footer from './components/Footer.vue'

  export default {
     components: {
    NavBar,
    Footer
}
  }
</script>

<style>
#app {
  font-family: 'Montserrat', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-weight: 300;
}
.bg-background{
 background-image: url('./assets/img/bg-second.png');
  color: #fff
;
}

</style>
