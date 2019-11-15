<template>
  <layout>
    <h1 class="text-2xl font-semibold mb-3">Welcome</h1>
    <p>Welcome to my first Inertia.js app!</p>
  </layout>
</template>

<script>
import Layout from '@/Shared/Layout';
import Login from '@/Pages/Login';

export default {
  components: {
    Layout,
    Login,
  },
}
</script>
