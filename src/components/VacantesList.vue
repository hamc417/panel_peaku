<template>
    <ul>
      <li v-for="(date, index) in vacantes" :key="index">
        <CardJob :title="date.title" :url="date.url" :company="date.company" :location="date.location" />
      </li>
    </ul>
  </template>
  
  <script>
  import CardJob from './CardJob.vue';
  
  export default {
    props: ['vacantes'],
    components: {
      CardJob,
    },
  };
  </script>
  