<template>
  <div class="container">
    <Hero />
    <Type />
    <Type />
    <Type />
    <Type />
  </div>
</template>

<script>
import Hero from '../components/Hero'
import Type from '../components/Type'

export default {
  name: 'Home',
  components: {
    Hero,
    Type,
  },
}
</script>

<style>
.container {
  margin: 0 auto;
  max-width: 48rem;
}
</style>
