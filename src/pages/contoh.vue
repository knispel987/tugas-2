<template>
 <div
  class="m-5 rounded-md flex w-fit p-2 text-3xl capitalize bg-blue-500 text-white hover:bg-indigo-400"
 >
  <router-link :to="{ name: 'home' }"> kembali</router-link>
 </div>
 <div>
  <p class="pt-6 uppercase text-center text-2xl sm:text-6xl font-semibold">contoh</p>
  <p class="space-y-9 text-2xl sm:text-4xl bg-pink-200 rounded-xl m-9 p-7">
   Dari sekelompok data terdapat 15 orang minum teh, 17 orang minum kopi, 12 orang minum
   kopi susu, dan 10 orang minum air jeruk. <br />
   Modus Dari minuman tersebut adalah ... <br />
   Jawaban =
   <span class="font-bold">Kopi</span>
  </p>
  <p class="space-y-9 text-2xl sm:text-4xl bg-pink-200 rounded-xl m-9 p-7">
   Data ulangan Matematika Diah adalah ...<br />
   Nilai : 6,7,8,9,10 <br />
   Frekuensi : 3,1,3,2,1 <br />
   Rata-rata nilai ulangan Diah adalah ... <br />
   Jawaban =
   <span class="font-bold">Kopi</span>
  </p>
 </div>
</template>

<script setup lang="ts">
useHead({
 title: "Contoh",
});
</script>

<route lang="yaml">
name: contoh
</route>
