<template>
    <router-link :to="to" :class="{ 'footer': applyCss }">Pedidos</router-link>
  </template>
  <script>
  export default {
    props: {
      to: {
        type: String,
        required: true
      },
      applyCss: {
        type: Boolean,
        default: false
      }
    }
  };
  </script>
  <style scoped>
    .footer {
        position: absolute;
    }
  </style>
  