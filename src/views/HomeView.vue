<script setup>
let ConcreteTechnology = [
  'Sieve Analysis of Aggregates','Blending of Aggregates','Aggregate Impact Value','Aggregate Crushing Value'
]
let QuantityEstimator = [
  'Construction Cost Calculator','Carpet Area / Built Up Area / Super built up area Calculator','Cement Concrete Calculator','Plastering Calculator'
]
let BlendingOfAggregates = [
  'Grading for Granular Sub-base Materials (GSB) (Grading - I)','Grading for Granular Sub-base Materials (GSB) (Grading - II)','Grading for Granular Sub-base Materials (GSB) (Grading - III)'
]
let RoadConstruction = ['Bitumen Prime Coat','Bitumen Tack Coat']
let SoilTest = ['Water Content Determination','Specific Gravity Determination','Sieve Analysis of Soil','Free Well Index of Soil','Liquid Limit of Soil']
</script>

<template>
  <main class="my-3 py-2 px-3">
    <div class="flex flex-col md:flex-row gap-4 justify-around">
      <!-- First Column -->
      <div class="md:basis-1/4">

        <div class="flex flex-col gap-4">

          <!-- 1 Concrete Technology -->
          <div class="">
            <!-- Repeating -->
            <h1 class="p-2 bg-slate-600 font-medium text-lg text-white">Concrete Technology<span class="ml-1 font-light text-xs">Calculator</span> </h1>
            <ul class="border-x-2">
              <li class="px-2 py-2 border-b hover:text-cyan-500" v-for="item in ConcreteTechnology" :key="item"><a href="#">{{item}}</a></li>
            </ul>
          </div>

          <!-- 2 Road Construction -->
          <div class="">
            <h1 class="p-2 bg-slate-600 font-medium text-lg text-white">Road Construction<span class="ml-1 font-light text-xs">Calculator</span> </h1>
            <ul class="border-x-2">
              <li class="px-2 py-2 border-b hover:text-cyan-500" v-for="item in RoadConstruction" :key="item"><a href="#">{{item}}</a></li>
            </ul>
          </div>
        </div>
        
      </div>

      <!-- Second Column -->
      <div class="md:basis-1/4">

        <div class="flex flex-col gap-4">

          <!-- 1 Quantity Estimator -->
          <div class="">
            <h1 class="p-2 bg-slate-600 font-medium text-lg text-white">Quantity Estimator<span class="ml-1 font-light text-xs">Calculator</span> </h1>
            <ul class="border-x-2">
              <li class="px-2 py-2 border-b hover:text-cyan-500" v-for="item in QuantityEstimator" :key="item"><a href="#">{{item}}</a></li>
            </ul>
          </div>
          <!-- 2 Soil Test -->
          <div class="">
            <h1 class="p-2 bg-slate-600 font-medium text-lg text-white">Soil Test<span class="ml-1 font-light text-xs">Calculator</span> </h1>
            <ul class="border-x-2">
              <li class="px-2 py-2 border-b hover:text-cyan-500" v-for="item in SoilTest" :key="item"><a href="#">{{item}}</a></li>
            </ul>
          </div>

        </div>

      </div>

      <!-- Third Column -->
      <div class="md:basis-1/2">

        <div class="flex flex-col gap-4">

          <div class="">
            <!-- 1 Blending of Aggregates -->
            <h1 class="p-2 bg-slate-600 font-medium text-lg text-white">Blending of Aggregates<span class="ml-1 font-light text-xs">Calculator</span> </h1>
            <ul class="border-x-2">
              <li class="px-2 py-2 border-b hover:text-cyan-500" v-for="item in BlendingOfAggregates" :key="item"><a href="#">{{item}}</a></li>
            </ul>
          </div>

        </div>

      </div>
    </div>
  </main>
</template>
