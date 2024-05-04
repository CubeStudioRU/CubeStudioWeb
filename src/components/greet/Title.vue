<template>
    <div class="flex flex-col items-center">
        <div class="text-zinc-50 font-black text-6xl text-center">
            {{ title }}
        </div>
        <div class="from-zinc-50 to-zinc-800 bg-clip-text text-transparent bg-gradient-to-r font-bold text-4xl text-center">{{ subtitle }}</div>
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