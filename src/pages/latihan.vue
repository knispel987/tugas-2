<template>
 <div
  class="m-5 rounded-md flex w-fit p-2 text-3xl capitalize bg-blue-500 text-white hover:bg-indigo-400"
 >
  <router-link :to="{ name: 'home' }"> kembali</router-link>
 </div>
 <p class="pt-6 uppercase text-center text-2xl sm:text-6xl font-semibold">latihan</p>

 <div class="space-y-9 text-2xl sm:text-4xl bg-pink-200 rounded-xl m-9 p-7">
  <p>
   Didalam sekantong kancing terdapat 28 kancing putih, 45 kancing merah, 37 kancing hitam
   dan 40 kancing biru. Modus dari warna kancing dalam kantong adalah . . .
  </p>
  <p>A. Putih</p>
  <p>B. Merah</p>
  <p>C. Hitam</p>
  <p>D. Biru</p>
 </div>

 <div class="space-y-9 text-2xl sm:text-4xl bg-pink-200 rounded-xl m-9 p-7">
  <p>
   Kelas : I, II, III, IV, V, VI <br />
   Banyak Siswa : 28, 24, 30, 32, 28, 26 <br />
   Rata-rata banyak siswa pada setiap kelas adalah ...
  </p>
  <p>A. 32</p>
  <p>B. 30</p>
  <p>C. 28</p>
  <p>D. 25</p>
 </div>
</template>

<script setup lang="ts"></script>

<route lang="yaml">
name: latihan
</route>
