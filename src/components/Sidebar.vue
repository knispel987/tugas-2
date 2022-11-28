<script setup></script>
<template>
 <nav class="fixed w-60 h-full">
  <ul
   class="text-4xl [&>*]:capitalize focus:[&>*]:outline focus:[&>*]:outline-1 hover:[&>*]:bg-gray-200 [&>*]:p-2 [&>*]:w-full [&>*]:flex h-full text-white bg-sky-400 overflow-auto"
  >
   <router-link :to="{ name: 'multimedia' }">multimedia</router-link>
   <router-link :to="{ name: 'materi' }">materi</router-link>
   <router-link :to="{ name: 'credits' }">credits</router-link>
   <router-link :to="{ name: 'about' }">about</router-link>
  </ul>
 </nav>
</template>
