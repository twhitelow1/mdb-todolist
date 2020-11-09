<template>
  <div class="app">
    <h1>This is your first component in Vue</h1>
    <h3>{{ message }}</h3>
  </div>
</template>

<script>
export default {
  name: "App",
  data: () => ({
    message: "Powered by MDB!",
  }),
};
</script>

<style>
.app {
  margin: 0 auto;
  font-family: sans-serif;
  background-color: #ccf7e2;
  padding: 10px;
  border-radius: 5px;
  max-width: 500px;
}
</style>