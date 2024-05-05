<script setup>
    import Title from '../greet/Title.vue';
    import Tile from '../utils/Tile.vue';
</script>

<template>
  <div class="flex flex-col h-screen justify-center">
    <Title subtitle="О Проекте" class="p-10"></Title>
    <div class="flex items-center justify-center">
      <div>
        <Tile icon="https://symbl.cc/i/webp/15/9190b6067010c1921ad4512914095d.webp" title="CubeShield" subtitle="Основан в 2021 году" size="size-96" background="https://minecraft-max.net/upload/resize_cache/iblock/08a/1296_729_2a3324da4e681fb601c5c153b16ea5bbf/hkk38ub8uassud4kxva2ufi7kysie2mq.webp"></Tile>
      </div>
      <div>
        <Tile icon="https://minotar.net/helm/Lyroq1s/600.png" title="Lyroq1s" subtitle="Владелец, Разработчик" size="h-44 w-96"></Tile>
        <Tile icon="https://minotar.net/helm/Dark_Novice2077/600.png" title="Dark_Novice" subtitle="Администратор, Геймдизайнер" size="h-44 w-96"></Tile>
      </div>
    </div>
  </div>
</template>