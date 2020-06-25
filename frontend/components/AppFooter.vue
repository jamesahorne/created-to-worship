<template>
  <footer class="footer">
    <p>Some footer info &copy;</p>
    <p>Contact at <a>this@email.address</a></p>
  </footer>
</template>

<script>
export default {
  name: 'AppFooter',
}
</script>

<style scoped>
.footer {
  text-align: center;
  padding: 2rem 0;
  max-width: 64rem;
  margin: 0 auto;
}

p {
  margin-bottom: 1rem;
}
</style>
