<template>
  <div class="home">
    <div class="home-top">
      <div class="container grid gap-4 mx-auto md:grid-cols-2 md:px-8 2xl:px-32 md:pb-4">
        <div>
          <p class="pt-16 text-5xl font-semibold text-large xl:text-8xl lg:text-7xl xl:pt-80 lg:pt-56 md:pt-40">
            Welcome to<br/>
            The Future
          </p>
        </div>
      
        <div>
          <img src="../assets/img/rocket.png" class="w-full animate" alt="" srcset="">
        </div>
      </div>
    </div>
    
    <div class="trip">
      <div class="container px-8 pt-5 pb-10 mx-auto md:px-8 2xl:px-32">
        <div class="grid gap-4 md:grid-cols-2">
          <div class="order-2 md:order-1">
          <img src="../assets/img/astro.png" class="w-full md:w-2/3 astro-ani" alt="" srcset="">
        </div>
        <div class="order-1 md:order-2">
          <p class="py-16 text-5xl font-semibold text-center text-large xl:text-7xl md:pt-20">
            Take A Trip!
          </p>
          <p class="pb-8 lg:text-2xl">Find out how our app helps you explore the
            possibilities of  <span class="font-semibold">Web 3</span>. We built it for you!
           </p>
            <p class="lg:text-2xl">
              All the awesome interactions and web experiences in one.</p>

            <div class="mt-12 text-center">
              <button class="px-12 py-5 text-3xl font-semibold rounded-full btn-primary">Launch App</button>
            </div>
        </div>
        </div>
      <div class="py-12 md:py-32">
        <div class="grid items-center gap-4 space-4 md:flex">
          <div class="pb-4 md:w-1/3">
            <p class="py-16 text-5xl font-semibold text-center text-large xl:text-7xl md:pt-20">
              Road Map
            </p>
            
              <p class="lg:text-2xl">
                Learn about our plans, ideas and future services. We intend to give you only memorable experiences.
              </p>

              <div class="mt-12 text-center">
                <button class="px-16 py-3 text-2xl font-semibold rounded-full md:text-3xl btn-primary">
                  <span class="text-xl font-light">Download</span> <br/>
                White Paper</button>
              </div>
          </div>
          <div class="order-2 w-full md:w-2/3 md:order-1 md:pl-3">
            <img src="../assets/img/raod-map.png" class="w-full" alt="" srcset="">
          </div>
        </div>
      </div>
      </div>
    </div>
  </div>
</template>
<style>
  .home-top{
    background-image:linear-gradient(to bottom, rgba(25, 1, 72, 0.82), rgba(25, 1, 72, 0.9)),
    url('../assets/img/welcome-home.png');
    background-size: contain;
    margin-top: -120px;
    z-index: -999;
    /* height: 100vh; */
  }
  .animate{
  position: relative;
  animation: mymove 5s infinite;
  }
  @keyframes mymove {
  from {top: 50px;}
  to {top: 0px;}
}
  .trip{
    background-image:linear-gradient(to bottom, rgba(25, 1, 72, 0.22), rgba(25, 1, 72, 0.3)), url('../assets/img/tripp.png');
    background-size: cover;
    background-repeat: no-repeat;
  }
  .astro-ani{
    position: relative;
  animation: myastro 5s infinite;
  animation-direction: reverse;
  }
  @keyframes myastro {
  0%   { left: 0px; top: 0px;}
  25%  {left: 50px; top: 0px;}
  50%  { left: 50px; top: 50px;}
  75%  { left: 0px; top: 50px;}
  100% { left: 0px; top: 0px;}
}
</style>
<script>

export default {
  name: 'HomeView',
  components: {
    // HelloWorld
  }
}
</script>
