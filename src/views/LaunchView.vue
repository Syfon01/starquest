<template>
  <div class="launch">
      <div class="container px-8 pt-5 pb-10 mx-auto md:px-8 2xl:px-32">
        <div class="my-10 text-right">
              <button class="px-12 py-5 text-3xl font-semibold rounded-full btn-primary">Connect Wallet</button>
            </div>
        <h2 class="text-3xl font-semibold text-center">Choose a vessel to take you on your journey</h2>
    </div>
  <flickity  class="flickity" ref="flickity" :options="flickityOptions">
  <NodeItem nodeTitle="Apollo 13" subTitle="Moon Rover"/>
  <NodeItem nodeTitle="Apollo 11" subTitle="Moon Rover"/>
  <NodeItem nodeTitle="Armada 23" subTitle="First Saturn Rover"/>
  <NodeItem nodeTitle="Apollo 12" subTitle="Moon Rover"/>
  <NodeItem nodeTitle="Apollo 13" subTitle="First Saturn Rover"/>
  <NodeItem nodeTitle="Apollo 13" subTitle="Moon Rover"/>

   
  </flickity>
</div>
</template>
<script>
import Flickity from 'vue-flickity'
import NodeItem from "../components/NodeItem"
export default {
  components: {
    Flickity,
    NodeItem
  },
  data () {
    return {
      flickityOptions: {
        // initialIndex: 5,
        prevNextButtons: false,
        pageDots: false,
        wrapAround: true,
        // freeScroll: true,
        "autoPlay": 5000,
        lazyLoad: 3,
        fullscreen: true
        // any options from Flickity can be used
      }
    }
  }
}
</script>
