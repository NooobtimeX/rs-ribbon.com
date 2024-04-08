<template>
  <div class="relative h-full">
    <img
      src="/panel/hero_section.webp"
      class="w-full h-auto rounded-b-none"
      alt="RS RIBBON PANEL"
      title="RS RIBBON PANEL"
      aria-label="RS RIBBON PANEL"
      width="1134px"
      height="327px"
    />
    <div class="grid grid-cols-4">
      <div>
        <img
          src="/panel/1.webp"
          class="w-full h-auto rounded-none rounded-es-xl"
          alt="เหรียญรางวัล"
          title="เหรียญรางวัล"
          ariaLabel="เหรียญรางวัล"
        />
      </div>
      <div v-for="image in images" :key="image.id">
        <img
          :src="image.src"
          class="w-full h-auto rounded-none"
          alt="เหรียญรางวัล"
          title="เหรียญรางวัล"
          ariaLabel="เหรียญรางวัล"
        />
      </div>
      <div>
        <img
          src="/panel/4.webp"
          class="w-full h-auto rounded-none rounded-br-xl"
          alt="เหรียญรางวัล"
          title="เหรียญรางวัล"
          ariaLabel="เหรียญรางวัล"
        />
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
const images = [
  {
    id: 2,
    src: "/panel/2.webp",
  },
  {
    id: 3,
    src: "/panel/3.webp",
  },
];
</script>
