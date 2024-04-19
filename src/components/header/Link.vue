
<template>
  <a :href="href" class="text-zinc-50 font-extrabold mx-3">{{content}}</a>
</template>

<script>
  export default {
    props: {
      content: String,
      href: String
    }
  }
</script>