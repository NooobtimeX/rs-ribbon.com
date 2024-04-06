<script setup lang="ts">
const title = "RS RIBBON | ริบบิ้นคุณภาพดี";
const description =
  "บริษัทจัดจำหน่ายริบบิ้นริบบิ้นคุณภาพดี โดยเรามีทั้งในรูปแบบหน้าร้านและออนไลน์พร้อมบริการจัดส่งทั่วประเทศไทย";
const image = "/panel/hero_section.webp";
useSeoMeta({
  title: title,
  ogTitle: title,
  twitterTitle: title,
  description: description,
  ogDescription: description,
  twitterDescription: description,
  ogImage: image,
  twitterImage: image,
  keywords: "RS RIBBON, ริบบิ้น, ริบบิ้นคุณภาพดี",
});
</script>
<template>
  <div>
    <AppHeroSection />
    <div class="text-center">
      <div class="mx-auto max-w-4xl">
        <div class="grid gap-1 md:grid-cols-3 my-2">
          <div class="md:order-1 order-2">
            <img
              src="/photo/all.jpg"
              class="mx-auto"
              alt="เหรียญรางวัล"
              title="เหรียญรางวัล"
              ariaLabel="เหรียญรางวัล"
            />
          </div>
          <div class="m-auto md:col-span-2 md:order-2 order-1">
            <h1 class="p-2">RS RIBBON</h1>
            <h2>ริบบิ้นคุณภาพดี</h2>
            <p>
              ริบบิ้นผ้าซาติน เกรดพรีเมียม มีให้เลือกหลากหลายสี ราคาม้วนละ 70
              บาทเท่านั้น!!
            </p>
            <ul>
              <li>✅ เกรดพรีเมียม</li>
              <li>✅ มีให้เลือกหลากหลายสี</li>
              <li>✅ ความกว้าง 20 มม.</li>
              <li>✅ ความยาว 100 หลา</li>
            </ul>
          </div>
        </div>
      </div>

      <AppAllColor />
    </div>

    <AppOurCustomer />
  </div>
</template>
