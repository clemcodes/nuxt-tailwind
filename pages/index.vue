<template>
  <body class="bg-gray-300">
    <div class="bg-gray-100 grid lg:grid-cols-2">
      <div class="px-8 py-12 max-w-md mx-auto sm:max-w-xl lg:px-12 lg:py-24">
        <img class="h-25" src="../assets/logo.png" alt="Prince's Trust, Youth Can Do It">
        <img class="mt-6 rounded-lg shadow-xl sm:mt-8 sm:h-96 sm:w-full sm:object-cover object-center lg:hidden" src="../assets/young-people.jpg" alt="a group of young people">
        <h1 class="mt-6 text-2xl font-bold text-gray-900 sm:mt-8 sm:text-4xl lg:text-3xl">Try New Things.
          <br class="hidden lg:inline"> 
          <span class="text-red-600">Unlock your potential.</span></h1>
        <p class="mt-2 text-gray-600 sm:mt-4 sm:text-xl">Our personal development programmes will help develop your confidence. Try new things, meet new people and develop essential skills at the same time.</p>
        <div class="mt-4">
          <a class="bg-red-500 px-5 py-3 inline-block rounded-lg shadow-lg text-white uppercase tracking-wider font-semibold text-sm sm:text-base" href="#">Book your first step</a>
        </div>
      </div> 
      <div class="hidden relative lg:block">
        <img class="absolute inset-0 w-full h-full object-cover object-center" src="../assets/young-people.jpg" alt="a group of young people">  
      </div>
   </div>  
    
  </body>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>
