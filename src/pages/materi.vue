<template>
 <div
  class="m-5 rounded-md flex w-fit p-2 text-3xl capitalize bg-blue-500 text-white hover:bg-indigo-400"
 >
  <router-link :to="{ name: 'home' }"> kembali</router-link>
 </div>
 <div>
  <p class="pt-6 uppercase text-center text-2xl sm:text-6xl font-semibold">materi</p>
  <div class="space-y-9 text-center text-2xl sm:text-4xl bg-pink-200 rounded-xl m-9 p-7">
   <h1 class="font-semibold">Rata-Rata (mean) dan Modus</h1>
   <p>
    Dari data yang terkumpul, kita dapat menentukan rata-rata hitung (mean) dan modus
    (data yang paling banyak muncul). Untuk menentukan mean dapat menggunakan rumus
    berikut ini
   </p>
   <img src="../images/mtkmean.png" alt="" />
  </div>
 </div>
</template>

<script setup lang="ts">
useHead({
 title: "Materi",
});
</script>

<route lang="yaml">
name: materi
</route>
