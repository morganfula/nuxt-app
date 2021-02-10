<template>
  <div class="container">
    <nuxt-link to="/users"><h1>Users</h1></nuxt-link>
  </div>
</template>

<script>
export default {};
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

h1 {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;

  font-weight: 300;
  font-size: 150px;
  color: #35495e;
  letter-spacing: 1px;
  transition: 0.2s ease-in;
}

a {
  text-decoration: none;
}

h1:hover {
  color: black;
}
</style>
