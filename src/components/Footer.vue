<template>
  <div class="py-10 bg-footer">
      <div class="container px-8 mx-auto md:px-8 2xl:px-32">
        <div class="grid items-center gap-4 space-4 md:flex">
          <div class="pb-4 border-r md:border-black md:w-2/5">
            <div class="relative grid grid-cols-2 gap-4"> 
              <div>
                <ul>
                  <li> <router-link to="/" class="block py-1 my-0 hover:text-blue-300">Home</router-link> </li>
                  <li> <router-link to="/launch" class="block py-1 my-0 hover:text-blue-300">Launch</router-link> </li>
                  <li> <router-link to="/white-paper" class="block py-1 my-0 hover:text-blue-300">White Paper</router-link> </li>
                  <li> <router-link to="/about" class="block py-1 my-0 hover:text-blue-300">About</router-link> </li>
                  <li> <router-link to="/contact" class="block py-1 my-0 hover:text-blue-300">Contact</router-link> </li>
                </ul>
              </div> 
              <div class="absolute bottom-0 right-0 px-3 py-2 mr-10 rounded-full bg-primary">
                social media here
              </div>
            </div>
          </div>
          <div class="w-full md:w-3/5 md:pl-3">
            
        <div class="grid items-end gap-4 space-4 md:flex">
          <div class=" md:w-1/2">
            <img src="../assets/img/logo.png" alt="" srcset="" class="w-40 h-20">
            <p class="mt-5 font-medium"> © Copyright 2022 StarQuest</p>
            </div>
          <div class="w-full md:w-3/5 md:pl-3">
            <div class="mb-10 text-right">
              <button class="px-12 py-5 text-3xl font-semibold rounded-full btn-primary">Launch App</button>
            </div>
            <form action="">
              <div class="flex mt-1 shadow-sm">
                  <input type="text" name="" id="" class=" px-3 text-center py-2.5 flex-1 block w-full rounded-l-full focus:ring-indigo-500 focus:border-indigo-500" placeholder="user@email.com">
                  <button class="btn inline-flex items-center px-2 py-2.5   rounded-r-full bg-primary">Subscribe </button>
               </div>
            <p class="pl-4 mt-0 text-sm italic">Get updates on our technologies!</p>
            </form>
          </div>
          </div>
        </div>
        </div>
      </div>
    
  </div>
</template> 

<script>
  export default {
    
  }
</script>

<style scoped>
  .bg-footer{
    background-color:rgba(54, 3, 157, 1);
;
  }
</style>