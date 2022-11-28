<script setup lang="ts">
useHead({
 title: "Other Pages",
});
</script>

<template>
 <div>
  <RouterLink :to="{ name: 'home' }">kembali</RouterLink>
 </div>
</template>

<route lang="yaml">
name: other-page
</route>
