<template>
  <nav>
    <ul>
      <li>Nav</li>
      <li>Item</li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'AppHeader',
}
</script>

<style scoped>
nav {
  padding: 2rem 4rem;
}
ul {
  display: flex;
  justify-content: flex-end;
}

li {
  display: block;
  margin-right: 2rem;
}
li:last-child {
  margin-right: 0;
}
</style>
