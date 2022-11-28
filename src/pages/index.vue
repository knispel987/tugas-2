<template>
 <div class="w-full">
  <h1 class="pt-6 uppercase text-center text-2xl sm:text-6xl font-semibold">
   media pembelajaran <br />
   Matematika
  </h1>
  <div>
   <div
    class="flex flex-col md:flex-row-reverse place-items-center place-content-center pt-6"
   >
    <img class="w-auto h-96 p-6" src="../images/matematika.jpeg" alt="" />
    <div
     class="[&>*]:px-6 [&>*]:py-3 [&>*]:rounded-xl [&>*]:text-white hover:[&>*]:bg-indigo-400 [&>*]:text-3xl [&>*]:capitalize [&>*]:bg-blue-500 [&>*]: [&>*]: [&>*]:outline [&>*]:outline-[5px] [&>*]:outline-indigo-600 text-center flex flex-col space-y-6 hover:[&>*]:shadow-2xl shadow-indigo-400"
    >
     <router-link :to="{ name: 'materi' }">
      <div class="flex flex-row space-x-5">
       <svg
        xmlns="http://www.w3.org/2000/svg"
        style="vertical-align: -0.125em"
        width="1em"
        height="1em"
        preserveAspectRatio="xMidYMid meet"
        viewBox="0 0 24 24"
       >
        <path
         fill="currentColor"
         d="M21 5c-1.11-.35-2.33-.5-3.5-.5c-1.95 0-4.05.4-5.5 1.5c-1.45-1.1-3.55-1.5-5.5-1.5S2.45 4.9 1 6v14.65c0 .25.25.5.5.5c.1 0 .15-.05.25-.05C3.1 20.45 5.05 20 6.5 20c1.95 0 4.05.4 5.5 1.5c1.35-.85 3.8-1.5 5.5-1.5c1.65 0 3.35.3 4.75 1.05c.1.05.15.05.25.05c.25 0 .5-.25.5-.5V6c-.6-.45-1.25-.75-2-1zm0 13.5c-1.1-.35-2.3-.5-3.5-.5c-1.7 0-4.15.65-5.5 1.5V8c1.35-.85 3.8-1.5 5.5-1.5c1.2 0 2.4.15 3.5.5v11.5z"
        />
        <path
         fill="currentColor"
         d="M17.5 10.5c.88 0 1.73.09 2.5.26V9.24c-.79-.15-1.64-.24-2.5-.24c-1.7 0-3.24.29-4.5.83v1.66c1.13-.64 2.7-.99 4.5-.99zM13 12.49v1.66c1.13-.64 2.7-.99 4.5-.99c.88 0 1.73.09 2.5.26V11.9c-.79-.15-1.64-.24-2.5-.24c-1.7 0-3.24.3-4.5.83zm4.5 1.84c-1.7 0-3.24.29-4.5.83v1.66c1.13-.64 2.7-.99 4.5-.99c.88 0 1.73.09 2.5.26v-1.52c-.79-.16-1.64-.24-2.5-.24z"
        />
       </svg>
       <p>materi</p>
      </div>
     </router-link>
     <router-link :to="{ name: 'contoh' }">
      <div class="flex flex-row space-x-5">
       <svg
        xmlns="http://www.w3.org/2000/svg"
        style="vertical-align: -0.125em"
        width="1em"
        height="1em"
        preserveAspectRatio="xMidYMid meet"
        viewBox="0 0 48 48"
       >
        <path
         fill="currentColor"
         fill-rule="evenodd"
         d="M39 13a3 3 0 0 0-3 3v2h6v-2a3 3 0 0 0-3-3Zm3 7h-6v16.5l3 4.5l3-4.5V20ZM6 9v30a3 3 0 0 0 3 3h22a3 3 0 0 0 3-3V9a3 3 0 0 0-3-3H9a3 3 0 0 0-3 3Zm14 6a1 1 0 0 1 1-1h8a1 1 0 1 1 0 2h-8a1 1 0 0 1-1-1Zm1 3a1 1 0 1 0 0 2h8a1 1 0 1 0 0-2h-8Zm-1 10a1 1 0 0 1 1-1h8a1 1 0 1 1 0 2h-8a1 1 0 0 1-1-1Zm1 3a1 1 0 1 0 0 2h8a1 1 0 1 0 0-2h-8Zm-9-3v3h3v-3h-3Zm-1-2h5a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1v-5a1 1 0 0 1 1-1Zm6.707-10.293a1 1 0 0 0-1.414-1.414L13 17.586l-1.293-1.293a1 1 0 0 0-1.414 1.414L13 20.414l4.707-4.707Z"
         clip-rule="evenodd"
        />
       </svg>
       <p>contoh</p>
      </div>
     </router-link>
     <router-link :to="{ name: 'latihan' }">
      <div class="flex flex-row space-x-5">
       <svg
        xmlns="http://www.w3.org/2000/svg"
        style="vertical-align: -0.125em"
        width="1em"
        height="1em"
        preserveAspectRatio="xMidYMid meet"
        viewBox="0 0 24 24"
       >
        <path fill="currentColor" d="M4 6H2v14c0 1.1.9 2 2 2h14v-2H4V6z" />
        <path
         fill="currentColor"
         d="M20 2H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zm-5.99 13c-.59 0-1.05-.47-1.05-1.05c0-.59.47-1.04 1.05-1.04c.59 0 1.04.45 1.04 1.04c-.01.58-.45 1.05-1.04 1.05zm2.5-6.17c-.63.93-1.23 1.21-1.56 1.81c-.13.24-.18.4-.18 1.18h-1.52c0-.41-.06-1.08.26-1.65c.41-.73 1.18-1.16 1.63-1.8c.48-.68.21-1.94-1.14-1.94c-.88 0-1.32.67-1.5 1.23l-1.37-.57C11.51 5.96 12.52 5 13.99 5c1.23 0 2.08.56 2.51 1.26c.37.61.58 1.73.01 2.57z"
        />
       </svg>
       <p>latihan</p>
      </div>
     </router-link>
    </div>
   </div>
  </div>
 </div>
</template>

<script setup lang="ts">
useHead({
 title: "Matematika",
});
const { t } = useI18n();
</script>

<route lang="yaml">
name: home
</route>
