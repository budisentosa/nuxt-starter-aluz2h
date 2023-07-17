<script setup>
definePageMeta({
  middleware: 'auth',
});
const username = useState('username');
</script>

<template>
  <div>
    <h1>Welcome {{ username }}</h1>
    <NuxtLink to="/">Home</NuxtLink>
  </div>
</template>
