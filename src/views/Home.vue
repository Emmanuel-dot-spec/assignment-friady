<template>
  <div class="home">
    <h1>Home Page</h1>
    <router-link :to="{ name: 'dashboard' }">Go to Dashboard</router-link>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
};
</script>
