<template>
  <nuxt-link class="block border" to="/songwriting">
    <h2 class="type__heading">Songwriting</h2>
    <p class="type__description">
      A short description about songwriting/why it's worshipful
    </p>
  </nuxt-link>
</template>

<script>
export default {
  name: 'Type',
}
</script>

<style scoped>
a {
  text-decoration: none;
  color: black;
  padding: 1rem;
  margin-bottom: 1rem;
}
</style>
