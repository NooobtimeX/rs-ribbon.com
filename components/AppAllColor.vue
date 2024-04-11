<template>
  <div class="grid gap-1 grid-cols-4 md:grid-cols-5 lg:grid-cols-6">
    <div v-for="image in images" :key="image.id">
      <img
        :src="image.src"
        class="w-full h-auto"
        alt="ริบบิ้น"
        title="ริบบิ้น"
        ariaLabel="ริบบิ้น"
        width="300px"
        height="300px"
      />
    </div>
  </div>
</template>

<script lang="ts" setup>
const images = [
  {
    id: 1,
    src: "/photo/01.webp",
  },
  {
    id: 5,
    src: "/photo/05.webp",
  },
  {
    id: 16,
    src: "/photo/16.webp",
  },
  {
    id: 25,
    src: "/photo/25.webp",
  },
  {
    id: 26,
    src: "/photo/26.webp",
  },
  {
    id: 34,
    src: "/photo/34.webp",
  },
  {
    id: 40,
    src: "/photo/40.webp",
  },
  {
    id: 43,
    src: "/photo/43.webp",
  },
  {
    id: 45,
    src: "/photo/45.webp",
  },
  {
    id: 52,
    src: "/photo/52.webp",
  },
  {
    id: 70,
    src: "/photo/70.webp",
  },
  {
    id: 76,
    src: "/photo/76.webp",
  },
  {
    id: 78,
    src: "/photo/78.webp",
  },
  {
    id: 101,
    src: "/photo/101.webp",
  },
];
</script>
