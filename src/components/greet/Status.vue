<template>
  <div class="text-center">
    <div class="font-semibold text-lg text-zinc-600">{{ content }}</div>
  </div>
</template>
  
<script>
    export default {
      props: {
        content: String
      }
    }
</script>