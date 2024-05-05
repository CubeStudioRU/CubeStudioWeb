<template>
  <div class="p-3">
    <img :src="background" class="object-cover absolute -z-10 opacity-50 rounded-2xl" :class="size" alt="">
    <div class="flex justify-center items-center border-zinc-600 border-2 rounded-2xl bg-gradient-to-r from-zinc-900 to-transparent hover:shadow-lg hover:shadow-zinc-800 transition-all" :class="size">
        <div class="">
            <img :src="icon" class="size-12 rounded-lg">
        </div>
        <div class="flex-col ml-3">
            <div class="text-4xl text-zinc-50 font-extrabold text-center">{{ title }}</div>
            <div class="text-sm text-zinc-500 font-medium text-center">{{ subtitle }}</div>
        </div>
    </div>
  </div>
</template>
  
<script>
    export default {
      props: {
        icon: String,
        title: String,
        subtitle: String,
        background: String,
        size: String
      }
    }
</script>