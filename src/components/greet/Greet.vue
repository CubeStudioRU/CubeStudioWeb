<script setup>
  import Title from './Title.vue';
  import Status from './Status.vue';
  import { ArrowDownCircleIcon } from '@heroicons/vue/20/solid';
</script>

<template>
  <div>
    <Title title="CUBESHIELD" subtitle="Уникальный проект для тебя" class="mt-52"></Title>
    <!--<Status content="Ееееее." class="mt-40"></Status>-->
    <div class="flex justify-center">
      <ArrowDownCircleIcon class="size-6 fill-zinc-50 animate-bounce mt-32"></ArrowDownCircleIcon>
    </div>
  </div>
</template>