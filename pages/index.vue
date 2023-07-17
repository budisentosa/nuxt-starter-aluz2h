<script setup>
const username = useState('username')
</script>

<template>
  <div>
    <h1>Home</h1>
    <p>In order to enter the secret page, you need to fill your username:</p>
    <p><input v-model="username" placeholder="Username" /></p>
    <NuxtLink to="/secret">Secret page</NuxtLink>
  </div>
</template>
