<template>
  <div>Welcome: {{ auth?.name }}</div>
</template>
<script setup>
import { usePage } from "@inertiajs/vue3";
const auth = usePage().props?.auth;
// console.log(auth);
</script>
