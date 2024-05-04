
<template>
  <a :href="href" class="">
    <img :src="'/src/assets/' + icon" class="size-6">
  </a>
</template>

<script>
  export default {
    props: {
      icon: String,
      href: String
    }
  }
</script>