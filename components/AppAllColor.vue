<template>
  <div class="grid gap-1 grid-cols-4 md:grid-cols-5 lg:grid-cols-6">
    <div v-for="image in images" :key="image.id">
      <img
        :src="image.src"
        class="w-full h-auto"
        alt="ริบบิ้น"
        title="ริบบิ้น"
        ariaLabel="ริบบิ้น"
      />
    </div>
  </div>
</template>

<script lang="ts" setup>
const images = [
  {
    id: 1,
    src: "/photo/01.jpg",
  },
  {
    id: 5,
    src: "/photo/05.jpg",
  },
  {
    id: 16,
    src: "/photo/16.jpg",
  },
  {
    id: 25,
    src: "/photo/25.jpg",
  },
  {
    id: 26,
    src: "/photo/26.jpg",
  },
  {
    id: 34,
    src: "/photo/34.jpg",
  },
  {
    id: 40,
    src: "/photo/40.jpg",
  },
  {
    id: 43,
    src: "/photo/43.jpg",
  },
  {
    id: 45,
    src: "/photo/45.jpg",
  },
  {
    id: 52,
    src: "/photo/52.jpg",
  },
  {
    id: 70,
    src: "/photo/70.jpg",
  },
  {
    id: 76,
    src: "/photo/76.jpg",
  },
  {
    id: 78,
    src: "/photo/78.jpg",
  },
  {
    id: 101,
    src: "/photo/101.jpg",
  },
];
</script>
