<template>
    <div class="bg-countItem text-center py-6 px-4">
      <div class="flex items-center">
        <div>
          <img :src="imageUrl" alt="">
        </div>
      <h3 class="text-2xl font-medium pl-4">{{countName}}</h3>
      </div>
      <h1 class="text-6xl pt-2 font-bold">{{count}}</h1>
  </div>
</template>

<script>
  export default {
    props: {
      countName: String,
      count: Number,
      imageUrl: String
    }
  }
</script>

