<template>
  <header class="w-full bg-gray-900 sticky top-0 z-50 mx-auto rounded-b-xl">
    <div class="max-w-7xl grid grid-1 md:grid-cols-3 mx-auto">
      <router-link
        :to="{ path: '/' }"
        class="flex items-center font-medium text-gray-900 title-font m-auto"
      >
        <div class="flex gap-2 mx-auto">
          <img
            src="\logo\RSTROPHY.webp"
            alt="RS RIBBON Logo"
            title="RS RIBBON Logo"
            width="50px"
            height="50px"
            class="m-1"
          />
          <h2 class="m-auto text-white font-bold">RS RIBBON</h2>
        </div>
      </router-link>
      <span class="text-center m-auto col-span-1 md:col-span-2">
        <router-link
          v-for="(link, index) in links"
          :key="index"
          :to="link.href"
          class="px-2 text-white font-bold"
        >
          {{ link.text }}
        </router-link>
      </span>
    </div>
  </header>
</template>
<script>
export default {
  data() {
    return {
      links: [
        { text: "หน้าแรก", href: "/" },
        { text: "เกี่ยวกับเรา", href: "/aboutus" },
        { text: "บทความ", href: "/blog" },
      ],
    };
  },
};
</script>
