<script setup>

</script>

<template>
  <div class="navbar">
    <RouterLink class="link" to="/">Home</RouterLink>
    <RouterLink class="link" to="/about">About</RouterLink>
  </div>

  <div class="main">
    <RouterView />
  </div>
</template>

<style scoped>
.navbar {
  width: 100%;
  padding: 20px;
  background-color: rgb(61, 61, 61);
}

.link {
  margin: 10px;
  text-decoration: none;
  color: white;
}

.main {
  width: 80%;
  margin: 0 auto;
}
</style>
