<template>
    <div class="bg-stat text-center py-8 px-4">
      <h3 class="text-3xl font-medium pl-4">{{statName}}</h3>
      <h1 class="text-6xl pt-4 font-bold">{{count}}</h1>
  </div>
</template>

<script>
  export default {
    props: {
      statName: String,
      count: Number || String,
    }
  }
</script>

