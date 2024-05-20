<template>
  <div class="min-h-screen flex items-center justify-center bg-gray-100">
    <div class="max-w-2xl w-full bg-white p-8 shadow-md rounded">
      <h2 class="text-2xl font-bold mb-6 text-center">Welcome to TaskMate!</h2>
      <p class="text-gray-700 text-center mb-4">Manage your tasks efficiently and effectively.</p>
      <div class="flex justify-center">
        <router-link to="/login" class="text-blue-500 hover:underline mr-4">Login</router-link>
        <router-link to="/register" class="text-blue-500 hover:underline">Register</router-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
};
</script>

<style scoped>
/* Add any additional styling if needed */
</style>
