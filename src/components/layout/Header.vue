<template>
  <div id="nav">
    <header class="header">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/todo-app">TodoApp</router-link>
    </header>
    <router-view/>
  </div>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style scoped>
  .header {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
  }

  .header a {
    color: #fff;
    padding-right: 5px;
    text-decoration: none;
  }
</style>