<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<div class="flex justify-center" style="max-width:420px; margin:50px auto;">
  <div class="w-full lg:max-w-full lg:flex">
      <div class="h-48 lg:h-auto lg:w-48 flex-none bg-cover rounded-t lg:rounded-t-none lg:rounded-l text-center overflow-hidden" style="background-image: url('picture.jpg')" title="River">
      </div>
      <div class="border-r border-b border-l border-gray-400 lg:border-l-0 lg:border-t lg:border-gray-400 bg-white rounded-b lg:rounded-b-none lg:rounded-r p-4 flex flex-col justify-between leading-normal">
        <div class="mb-8">
         
          <div class="text-gray-900 font-bold text-xl mb-2">Profile Description</div>
          <p class="text-gray-700 text-base">I am a student currently attending Politeknik Brunei, taking Website Development. I aspire to become someone that makes an impact on the workforce of my country when i do get a job.
            Though, that can wait until I complete my Degree in University. </p>
        </div>
        <div class="flex items-center">
          <img class="w-10 h-10 rounded-full mr-4 object-cover" src="./assets/picture.jpg" alt="Avatar of Writer">
          <div class="text-sm">
            <strong class="text-gray-900 leading-none">Hariz Razali</strong>
            <p class="text-gray-600">Bandar Seri Begawan, Brunei.Bahit</p>
          </div>
        </div>
      </div>
    </div>  
</div> 
</body>
</template>

<style scoped>
body {
  background-color: #EDF2F7
}

</style>
