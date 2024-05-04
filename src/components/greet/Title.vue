<template>
    <div class="flex flex-col items-center">
        <div class="text-zinc-50 font-black text-6xl text-center">
            {{ title }}
        </div>
        <div class="from-lime-300 via-red-400 to-blue-600 bg-clip-text text-transparent bg-gradient-to-r font-bold text-4xl text-center animate-gradient">{{ subtitle }}</div>
    </div>
  </template>
  
  <script>
    export default {
      props: {
        title: String,
        subtitle: String
      }
    }
  </script>