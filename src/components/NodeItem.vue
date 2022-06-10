<template>
  <div class="carousel-cell">
      <div class="py-4 text-center md:px-12 inner">
        <img src="../assets/img/rocket-img.png" alt="" class="w-40 h-40" srcset="">
        <h2 class="text-2xl font-semibold">{{nodeTitle}}</h2>
        <p>{{subTitle}}</p>
        <div class="my-2">
          <input type="text" placeholder="Node Name" class="py-2 text-sm text-center rounded-lg text-slate-500 node-input"/>
        </div>
        <div class="my-2">
          <input type="text" placeholder="Node Name" class="py-2 text-sm text-center rounded-lg text-slate-500 node-input"/>
        </div>
        <div>
          <button class="px-3 py-2 font-semibold bg-white rounded-lg btn tx-primary">+ Create Node</button>
        </div>
      </div>
    </div>
</template>

<script>
  export default {
      props: {
    nodeTitle: String,
    subTitle: String
  }
  }
</script>

<style scoped>
.carousel-cell {
  width: 20%;
  min-height: 500px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.carousel-cell .inner {
  display: block;
  max-width: 100%;
  max-height: 100%;
  background: rgba(74, 20, 182, 1);
box-shadow: 8px 6px 33px 0px rgba(1, 21, 51, 0.7);
border-radius: 20px;
  /* dim unselected */
  opacity: 0.7;
  transform: scale(0.75);
  filter: blur(2px);
}

/* brighten selected image */
.carousel-cell.is-selected .inner {
  opacity: 1;
  transform: scale(1.2);
  filter: none;
}
.carousel-cell:before{
  display: block;
  content: '';
}
.node-input{
  background: rgba(45, 4, 129, 1);
;
}
</style>